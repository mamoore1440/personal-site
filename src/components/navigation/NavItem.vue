<template>
  <a
    v-if="href.startsWith('http://') || href.startsWith('https://')"
    :href="href"
    :class="`p-3 hover:underline align-middle transition ${active ? 'text-primary-light dark:text-primary-dark' : 'dark:text-white'}`"
  >
    <slot />
  </a>
  <nuxt-link
    v-else
    :to="href"
    :class="`p-3 hover:underline align-middle transition ${active ? 'text-primary-light dark:text-primary-dark' : 'dark:text-white'}`"
  >
    <slot />
  </nuxt-link>
</template>

<script>
export default {
  name: 'nav-item',
  props: {
    href: {
      type: String,
      default: ''
    },
    active: {
      type: Boolean,
      default: false
    }
  },
};
</script>

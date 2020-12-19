<script>
export default {
    name: 'add-hero-btn',
    props: {
        text: String,
    }
}
</script>

<template>
    <a class="f6 link dim br3 ba bw2 ph3 pv2 mb2 dib black" href="#0"
        @click="$emit('add-hero', true)"
      >{{ text }}</a>
</template>
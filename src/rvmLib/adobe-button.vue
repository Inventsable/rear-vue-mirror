<template lang="html">
  <div class="adobe-btn">
    <span :class="'adobe-icon-' + icon"></span>
  </div>
</template>

<script>
export default {
  props: ['icon'],
  data() {
    return {

    }
  },
  methods: {

  },
}
</script>

<style lang="css">

:root {
  --borderWidth: 1.35px;
  --btnPadding: .0625rem .5rem;
  --btnMargin: auto .035rem;
  --btnHeight: 1.75rem;
  --btnHeightMax: 25.17px;
  --btnWidth: 1.25rem;
}

[class^="adobe-btn"] {
  font-size: 14px;
  padding: var(--btnPadding);
  margin: var(--btnMargin);
  min-width: var(--btnWidth);
  height: var(--btnHeight);
  /* max-height: var(--btnHeightMax); */
  border-width: var(--BorderWidth);
  border-color: var(--colorBorder);
  border-style: solid;
  user-select: none;
  cursor: pointer;
}

</style>

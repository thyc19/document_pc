<template>
  <!-- <div class="custom-icons-list"> -->
  <div>
    <time-icon />
  </div>
  <!-- </div> -->
</template>
<script>
// 发文拟稿
const Time = {
  template: `
  <svg xmlns="http://www.w3.org/2000/svg" width="15.033" height="15" viewBox="0 0 15.033 15">
  <g id="组_3362" data-name="组 3362" transform="translate(-161.28 -156.16)">
    <path id="路径_2466" data-name="路径 2466" class="cls-1" d="M176.3,171.16H161.28v-15h15.033v15Zm-14.035-.987h13.059V157.147H162.267Z"/>
    <path id="路径_2467" data-name="路径 2467" class="cls-1" d="M330.224,502.784h5.351v.987h-5.351Zm-2.544,0h1.272v.987H327.68Zm2.544,2.906h5.351v.987h-5.351Zm-2.544,0h1.272v.987H327.68Z" transform="translate(-162.836 -339.201)"/>
    <path id="路径_2468" data-name="路径 2468" class="cls-1" d="M327.68,283.943h1.272v.987H327.68Zm4.572,1.776-1.623-1.634.691-.691.932.932,2.215-2.215.7.7Z" transform="translate(-162.836 -123.255)"/>
  </g>
</svg>
  `
};
const TimeIcon = {
  template: `
    <a-icon :component="Time" />
  `,
  data() {
    return {
      Time
    };
  }
};

export default {
  name: "SvgIcon",
  components: {
    TimeIcon,
  },
  created(){
  }
};
</script>
<style scoped>
.custom-icons-list >>> .anticon {
  margin-right: 6px;
}
</style>

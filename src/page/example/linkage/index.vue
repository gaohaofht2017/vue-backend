<template>
    <div>
        <v-distpicker
            province="安徽省"
            city="合肥市"
            area="蜀山区"
        />
        <!-- province	省份（选填）	String	省份名	null
            city	城市（选填）	String	城市名	null
            area	地区（选填）	String	地区名	null
            type	类型（选填，默认 select）	String	mobile	null
            disabled	是否禁用（选填，默认 false，且 type='mobile' 时无效）	Boolean	true, false	false
            hide-area	隐藏地区（选填）	Boolean	true, false	false
            onlu-province	只显示省份（选填）	Boolean	true, false	false
            static-placeholder	是否将占位符显示为已经选择的项（仅 type='mobile' 时有效）	Boolean	true, false	false
            placeholders	占位符（选填）	Object	province, city, area	{ province: '省', city: '市', area: '区' }
            wrapper	外层 Class（选填）	String	customize	address
            address-header	address-header 样式（选填，类型必须为 mobile）	String	customize	address-header
            address-container	address-container 样式（选填，类型必须为 mobile）	String	customize	address-contaniner -->
        <span> </span>
    </div>
</template>

<script>
import VDistpicker from "v-distpicker";
export default {
  components: { VDistpicker },
  data() {
    return {};
  },

  methods: {}
};
</script>

<style lang='less' rel='stylesheet/less'>
</style>

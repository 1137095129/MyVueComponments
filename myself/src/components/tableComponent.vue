<template>
    <table :style="{'width':wid,'height':heig,'color':col,'font':fo,'table-border':table_bor}">
        <slot name="tr"></slot>
    </table>
</template>
<script>
export default {
    // name:"table-component",
    // data(){
    //     return {
    //         wid:this.width,
    //         heig:this.height,
    //         col:this.color,
    //         fo:this.font,
    //         bor:this.border,
    //         table_bor:this.table_border
    //     }
    // },
    // props:{
    //     // 表格宽度
    //     width:{
    //         type:Number,
    //         default:10
    //     },
    //     // 表格高度
    //     height:{
    //         type:Number,
    //         default:20
    //     },
    //     // 表格字体颜色
    //     color:{
    //         type:String,
    //         default:"black"
    //     },
    //     // 表格字体样式
    //     font:{
    //         type:String,
    //         default:"宋体"
    //     },
    //     // 表格边框样式
    //     border:{
    //         type:String,
    //         default:"1px solid black"
    //     },
    //     // 表格内边框，默认合并
    //     table_border:{
    //         type:String,
    //         default:"collapse"
    //     }
    // },
    // watch:{
    //     width:(val)=>{
    //         this.wid=val
    //     },
    //     height:(val)=>{
    //         this.heig=val
    //     },
    //     color:(val)=>{
    //         this.col=val
    //     },
    //     font:(val)=>{
    //         _this.fo=val
    //     },
    //     border:(val)=>{
    //         _this.bor=val
    //     },
    //     table_border:(val)=>{
    //         _this.table_bor=val
    //     }
    // },
    // methods:{
    //     getTableStyles:()=>{
    //         return {
    //             "width":this.width,
    //             "height":this.height,
    //             "color":this.color,
    //             "font":this.font,
    //             "border":this.border,
    //             "table-collapse":this.table_border
    //         }
    //     }
    // },
    // computed(){
    //     this.getTableStyles();
    // }
}
</script>
<style scoped>

</style>
<template>
    <div class="vue-echarts-sunburst vue-chart" ref="echartsCanvas">

    </div>
</template>

<script>
    import 'echarts/lib/chart/sunburst';
    import {echartsCoreMixin} from "../echarts-core";
    //应用维度 encode
    export default {
        name: "vue-echarts-sunburst",
        mixins: [echartsCoreMixin],
        props: {

        },
        data(){
            return {
                seriesModel: {
                    type: 'sunburst',
                    name: '',
                    data: [],
                    label: {
                        show: false,
                        position: 'inside'
                    }
                }
            }
        },
        components: {
        },
        methods: {

        },
        mounted(){

        }
    }
</script>

<style lang="scss">
</style>

<script>
    import Sales from './../Components/Widgets/Sales';
    import Metrics from './../Components/Widgets/Metrics';
    import Activities from './../Components/Widgets/Activities';

    export default {
        components: {
            Sales,
            Metrics,
            Activities
        },

        data() {
            return {
                title: this.__('Dashboard')
            };
        }
    }
</script>

<template>
    <div class="row">
        <div class="col-12">
            <metrics class="row"></metrics>
        </div>
        <div class="col-6">
            <activities></activities>
        </div>
        <div class="col-6">
            <sales></sales>
        </div>
    </div>
</template>

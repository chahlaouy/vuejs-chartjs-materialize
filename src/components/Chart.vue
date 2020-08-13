<template>
    <div>
        <form action="" class="col s12">
            <div class="row">

                <div class="input-field col s3">
                    <input type="text" name="temp" id="temp" class="validate">
                    <label for="temp">Temperature</label>
                </div>
                <div class="input-field col s3">
                    <input type="text" name="hum" id="hum" class="validate">
                    <label for="hum">Humidity</label>
                </div>
                <div class="input-field col s3">
                    <input type="text" name="pot" id="pot" class="validate">
                    <label for="pot">Potentio</label>
                </div>
                <div class="col s3">
                   <div class="row">
                       <div class="col s6">
                            <a class="waves-effect waves-light btn purple"><i class="material-icons left">cloud_download</i></a>
                       </div>
                       <div class="col s6">
                            <a class="waves-effect waves-light btn"><i class="material-icons left">cloud_upload</i></a>
                       </div>
                   </div>
                </div>
            </div>

        </form>
    </div>
</template>

<script>
export default {
    
}
</script>

<style scoped>

</style>
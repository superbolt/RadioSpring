
<template>
    <div id="player_container" class="player-container">
        <!--<window-controls></window-controls>-->
        <bezel></bezel>
        <audio-element></audio-element>
    </div>
</template>

<script>
    //import WindowControls from './WindowControls/WindowControls'
    import Bezel from './PlayerView/Bezel'
    import AudioElement from './PlayerView/AudioElement'

    export default {
        components: {
            // WindowControls,
            Bezel,
            AudioElement
        },
        name: 'player-view'
    }
</script>



<style lang="scss" scoped>

    @import "./app/src/scss/settings.scss";

    .player-container {
        display: flex;
        flex-wrap: wrap;
        margin: 5px;// 8px;
        min-height: 43px;
    }

</style>

<script>
    import { showAverages } from '../store/store.js';
    import ShowAverages from './Option_ShowAverages.svelte';
    import ExcludeRideTypes from './Option_ExcludeRideTypes.svelte';
    import ShowSameDayRides from './Option_ShowSameDayRides.svelte';
    import RidesToShow from './Option_RidesToShow.svelte';
</script>


<h2>Options</h2>
<form>
    <RidesToShow />
    <!-- <ShowAverages /> Removed after changing averages appearance -->
    <ShowSameDayRides />
    <ExcludeRideTypes />
</form>

<style>
    form {
        margin-left: 10px;
    }
</style>
    
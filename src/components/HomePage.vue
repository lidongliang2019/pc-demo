<template>
    <div>
      <Header></Header>
      <Banner></Banner>
      <RightBox></RightBox>
      <IndexNewHouse></IndexNewHouse>
      <DataStats></DataStats>
      <TwoHandHouse></TwoHandHouse>
      <SmallCommunity></SmallCommunity>
      <AdvertisingSpace></AdvertisingSpace>
    </div>
</template>

<script>
  import Header from "./Header";
  import Banner from "./Banner";
  import IndexNewHouse from "./IndexNewHouse";
  import TwoHandHouse from "./TwoHandHouse";
  import RightBox from "./RightBox";
  import NewHouses from "./NewHouses";
  import DataStats from "./dataStats";
  import SmallCommunity from "./SmallCommunity";
  import AdvertisingSpace from "./AdvertisingSpace";
    export default {
        name: "HomePage",
        components: {
            AdvertisingSpace,
            SmallCommunity,  DataStats, NewHouses, RightBox, TwoHandHouse, IndexNewHouse, Banner, Header}
    }
</script>

<style scoped>

</style>

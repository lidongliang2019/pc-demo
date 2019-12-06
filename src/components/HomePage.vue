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
      <BaiKe></BaiKe>
      <NewCenterMessage></NewCenterMessage>
      <HelpMePrice></HelpMePrice>
      <Foot></Foot>
    </div>
</template>

<script>
  import Header from "./homePageCompnents/Header";
  import Banner from "./homePageCompnents/Banner";
  import IndexNewHouse from "./homePageCompnents/IndexNewHouse";
  import TwoHandHouse from "./homePageCompnents/TwoHandHouse";
  import RightBox from "./homePageCompnents/RightBox";
  import NewHouses from "./homePageCompnents/NewHouses";
  import DataStats from "./homePageCompnents/dataStats";
  import SmallCommunity from "./homePageCompnents/SmallCommunity";
  import AdvertisingSpace from "./homePageCompnents/AdvertisingSpace";
  import BaiKe from "./homePageCompnents/BaiKe";
  import NewCenterMessage from "./homePageCompnents/NewCenterMessage";
  import HelpMePrice from "./homePageCompnents/HelpMePrice";
  import Foot from "./Common/Foot";
    export default {
        name: "HomePage",
        components: {
            Foot,
            HelpMePrice,
            NewCenterMessage,
            BaiKe,
            AdvertisingSpace,
            SmallCommunity,  DataStats, NewHouses, RightBox, TwoHandHouse, IndexNewHouse, Banner, Header}
    }
</script>

<style scoped>

</style>

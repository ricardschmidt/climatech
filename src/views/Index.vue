<template>
    <div>
        <hero></hero>
        <customers></customers>
        <mission></mission>
        <cards></cards>
        <vision></vision>
    </div>
</template>
<script>
import Hero from "./components/Hero";
import Customers from "./components/Customers";
import Mission from "./components/Mission";
import Cards from "./components/Cards";
import Vision from "./components/Vision";

export default {
  name: "components",
  components: {
    Hero,
    Customers,
    Mission,
    Cards,
    Vision,
  }
};
</script>

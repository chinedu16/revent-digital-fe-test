<template>
  <div>
    <h3 class="title-header font-bold text-center leading-8 md:text-3xl text-2xl">{{title}}</h3>
    <underline-icon />
  </div>
</template>

<script>
import UnderlineIcon from "./Icons/UnderlineIcon";
export default {
    components: {
        UnderlineIcon
    },
    props: {
        title: {
            default: "",
            type: String
        }
    }
}
</script>

<style>
.title-header  {
    width: fit-content;
}
</style>
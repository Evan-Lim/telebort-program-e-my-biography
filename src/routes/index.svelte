<script>
import Header from "$lib/Header.svelte";
import Section from "$lib/Section.svelte";
import Footer from "$lib/Footer.svelte";
let myInfo = {
    title: "Info",
    item1: "Evan Lim Hong Yan",
    item2: 13,
    item3: "SM Sains Pendang",
}
let myHobbies = {
    title: "Hobbies",
    item1: "Playing Piano",
    item2: "Coding",
    item3: "Cycling",
}
let myPersonality = {
    title: "Personality",
    item1: "Quiet",
    item2: "Humble",
    item3: "Kind",
}
</script>
<Header title={"My Biography"} />
<Section {...myInfo} />
<Section {...myHobbies} />
<Section {...myPersonality} />
<Footer gitHub={"https://github.com/Evan-Lim/telebort-program-e-my-biography"}/>
<style>

</style>
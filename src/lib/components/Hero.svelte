<script>
    import ButtonGroup from "./ui/button-group/button-group.svelte";
    import Button from "./ui/button/button.svelte";
</script>

<style>
    .hero {
        background-image: url('/bg.png');
        background-size: cover;
        background-position: center;
    }
</style>

<div class="hero relative w-full h-screen">
    <div class="absolute inset-0 flex flex-col items-center justify-center z-10">
        <h2 class="mt-0">Availible now!</h2>
        <br>
        <ButtonGroup>
            <Button href="https://voidcreature3892.itch.io/neonblade">Download (itch.io)</Button>
            <Button variant="secondary" href="#">Speedrun leaderboard (coming soon)</Button>
        </ButtonGroup>
    </div>
</div>

<script>
    import ButtonGroup from "./ui/button-group/button-group.svelte";
    import Button from "./ui/button/button.svelte";
</script>

<style>
    .hero {
        background-image: url('/ss/Screenshot_2025-11-03_183338.png');
        background-size: cover;
        background-position: center;
    }
</style>

<div class="hero relative w-full h-screen">
    <div class="absolute inset-0 flex flex-col items-center justify-center z-10 bg-background/50">
        <img src="/logo.png" alt="neonblade logo" class="max-w-[50%] mb-6">
        <ButtonGroup>
            <Button href="https://voidcreature3892.itch.io/neonblade">Download (itch.io)</Button>
            <Button href="https://drive.google.com/file/d/1fpOSxy9WJSkYpFOLHxkvbff2MkNiYlP8/view">Download (Google Drive mirror)</Button>
        </ButtonGroup>
    </div>
</div>

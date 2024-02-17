
<script>
    import "../app.css";
    import MdiGithub from '~icons/mdi/github'
</script>

<nav class="flex w-full justify-center mt-8">
    <div class="flex felx-col justify-between w-11/12 h-10">
        <div class="w-20 h-full text-text">
            <a href="https://github.com/korneliushen">
                <MdiGithub class='w-16 h-16'></MdiGithub>
            </a>
        </div>
        <div class="h-full flex space-x-20">
            <a class="nav" href="https://github.com/korneliushen?tab=repositories">
                <p class="text-text text-2xl">Prosjekter</p>
            </a>
            <a class="nav" href="/">
                <p class="text-text text-2xl">Om meg</p>
            </a>
            <a class="nav" href="/">
                <p class="text-text text-2xl">Kontakt</p>
            </a>
        </div>
    </div>
</nav>

<slot>
    
</slot>
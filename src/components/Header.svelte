<script>
    export let y;

    let tabs = [
        { name: "Projects", link: "#projects" },
        { name: "About me", link: "#about" },
        //{ name: "Projects", link: "/projects" },
    ];
</script>

<header>
    <h1>
        <b>Hardik</b> Patel
    </h1>
    <div class="">
        {#each tabs as tab, index}
            <a>
                <p>{tab.name}</p>
            </a>
        {/each}
    </div>
</header>
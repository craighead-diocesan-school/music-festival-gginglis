<script>
    import { page } from "$app/stores";
</script>

<div class="banner">
    <header>
        <h1>Sunburst Festival</h1>
    </header>

    <nav>
        <div class="right">
            <a class:is-active={$page.url.pathname == "/"} href="/">home</a>
        </div>
        <div class="left">
            <a
                class:is-active={$page.url.pathname == "/general"}
                href="/general">general</a
            >
        </div>
        <div class="left">
            <a class:is-active={$page.url.pathname == "/acts"} href="/acts"
                >acts</a
            >
        </div>
        <div class="left">
            <a
                class:is-active={$page.url.pathname == "/accommodation"}
                href="/accommodation">accommodation</a
            >
        </div>
    </nav>
</div>

<style>
    @import url("https://fonts.googleapis.com/css2?family=KoHo:wght@600&family=Kufam:ital,wght@0,400..900;1,400..900&display=swap");
    h1 {
        text-transform: uppercase;
        font-family: "Kufam", sans-serif;
        color: #9468cf;
        font-size: 3rem;
        font-weight: 700;
        background-color: #f6e9ff;
        padding: 40px;
    }

    nav {
        background-color: #f6e9ff;
        font-family: "KoHo", sans-serif;
        font-weight: 500;
        padding: 60px 77.5px 50px 275px;
        display: flex;
    }
    a {
        color: #9468cf;
        font-size: 1.65rem;
        margin: 15px;
        transition: 0.4s;
    }

    a:hover {
        color: #5c3c9c;
        transition: 0.4s;
    }

    .left {
        border-left: 1px solid #9568cf89;
    }

    .banner {
        display: flex;
        flex-direction: row;
        border-bottom: 2px solid #9568cf89;
    }

    .is-active {
        color: #5c3c9c;
    }
</style>

<script>
    export let heading;
    export let translation;
    export let info;
    export let src;
</script>

<div class="content">
    <img {src} alt="" />
    <h2>{heading}</h2>
    <h3>{translation}</h3>
    <p>{info}</p>
</div>

<style>
    h2 {
        font-family: "Kufam", sans-serif;
        color: #5c3c9c;
        font-size: 3rem;
        font-weight: 700;
        margin: 25px 25px 0px;
    }
    h3 {
        font-family: "Kufam", sans-serif;
        color: #9468cf;
        font-size: 2.25rem;
        font-weight: 700;
        margin: 0px 20px 20px 50px;
    }

    p {
        font-family: "KoHo", sans-serif;
        font-weight: 500;
        color: #9468cf;
        font-size: 1.3rem;
        text-align: justify;
        margin: 50px;
    }

    img {
        width: 700px;
    }

    .content {
        display: flexbox;
    }
</style>

<script>
    import Banner from "$lib/Banner.svelte";
    import Footer from "$lib/Footer.svelte";
</script>

<Banner />

<main>
    <div class="image">
        <img src="/hanny-naibaho.jpg" alt="Hanny Naibaho" />
    </div>
    <div class="text">
        <h2>general</h2>
        <h3>whānui</h3>
        <p>
            Welcome to the ultimate music festival experience! Get ready for a
            day filled with live music, great food, and unforgettable memories.
        </p>
        <p>
            Our festival features a diverse lineup of talented musicians from
            different genres, sure to satisfy every taste in music. With
            multiple stages set up throughout the venue, you can easily move
            from one act to the next, discovering new favorites and enjoying
            classic hits.
        </p>
        <p>
            From up-and-coming artists to established headliners, we have
            curated an exciting lineup that will keep you dancing and singing
            along all day long. Our festival is the perfect opportunity to
            discover new music, see your favorite artists live, and make lasting
            memories with friends and family.
        </p>
        <p>
            But the music is just the beginning. Our festival also boasts an
            impressive selection of food vendors, offering everything from
            classic festival fare to more gourmet options. You won't go hungry
            with the delicious treats and refreshing beverages available
            throughout the venue.
        </p>
        <p>
            In addition to the music and food, our festival also features a
            variety of activities to keep you entertained throughout the day.
            From art installations to merchandise booths, there is something for
            everyone to enjoy. You can even capture the memories with our
            festival photo booths and snap a selfie with your favorite artists.
        </p>
        <p>
            So don't miss out on this one-of-a-kind music festival experience.
            Get your tickets now and join us for a day of music, fun, and
            community. We can't wait to see you there!
        </p>
    </div>
</main>

<Footer />

<style>
    h2 {
        font-family: "Kufam", sans-serif;
        color: #5c3c9c;
        font-size: 3rem;
        font-weight: 700;
        margin: 20px 40px 0px;
    }
    h3 {
        font-family: "Kufam", sans-serif;
        color: #9468cf;
        font-size: 2.25rem;
        font-weight: 700;
        margin: -33px 10px 20px 182.5px;
    }
    main {
        background-color: #f6e9ff;
        display: flex;
    }

    p {
        font-family: "KoHo", sans-serif;
        font-weight: 500;
        color: #9468cf;
        font-size: 1.3rem;
        text-align: justify;
        margin: 19px;
    }

    img {
        width: 720px;
    }

    .text {
        width: 700px;
        margin-top: 15px;
    }
</style>

<script>
    import Banner from "$lib/Banner.svelte";

    import Footer from "$lib/Footer.svelte";
</script>

<Banner />

<main>
    <div class="text">
        <h2>acts</h2>
        <h3>ngā mahi</h3>
        <p>
            The music festival boasts an exciting lineup of talented musicians
            from a variety of genres, promising a diverse and entertaining
            experience for all attendees.
        </p>
        <p>
            On the main stage, the headliners are a mix of established and
            up-and-coming acts, guaranteed to draw in large crowds. The first
            headliner is a popular rock band, known for their high-energy
            performances and catchy hooks. They will be followed by a
            chart-topping pop artist, whose upbeat and infectious hits are sure
            to get the crowd dancing and singing along. The final headliner is a
            legendary hip-hop artist, whose iconic rhymes and charismatic stage
            presence will bring the festival to a thrilling close.
        </p>
        <p>
            On the second stage, indie bands and singer-songwriters showcase
            their unique styles and sounds. The performers on this stage are
            often the most buzzed-about acts of the festival, with a loyal and
            passionate following. From dreamy shoegaze bands to alternative rock
            acts, the second stage offers a more intimate and personal
            experience for music lovers looking to discover new artists.
        </p>
        <p>
            The third stage is dedicated to up-and-coming artists from different
            genres, providing a platform for emerging talent to showcase their
            skills and gain exposure. This stage is a great opportunity for
            attendees to discover new artists and support the next generation of
            musicians.
        </p>
        <p>
            Throughout the festival, DJs and electronic acts keep the energy up
            between sets, playing a mix of classic and contemporary dance tracks
            that will keep the crowd moving and grooving.
        </p>
        <p>
            Overall, the music festival offers a diverse and exciting lineup
            that caters to different tastes and styles. From established
            headliners to emerging talent, the festival promises a memorable and
            thrilling musical experience for all attendees.
        </p>
    </div>
    <div class="image">
        <img
            src="/samuel-regan-asante.jpg"
            alt="Samuel Regan Asante"
            title="Samuel Regan Asante"
        />
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
        margin: -37px 10px 20px 110px;
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
        width: 730px;
    }

    .text {
        width: 730px;
        margin-top: 15px;
    }
</style>

<script>
    import Header from "$lib/Header.svelte";
    import Nav from "$lib/Nav.svelte";
    import Card from "$lib/Card.svelte";
    import Footer from "$lib/Footer.svelte";
</script>

<div class="header">
    <Header />

    <Nav />
</div>
<main>
    <Card
        heading="accommodation"
        translation="whare noho"
        src="/hanny-naibaho.jpg"
        info="Experience the ultimate music festival adventure with our tent accommodation packages! With our comfortable and convenient tents, you can immerse yourself in the festival atmosphere and stay close to all the action. Our tents are spacious and come equipped with everything you need for a comfortable stay. With comfortable beds, pillows, and blankets, you can get a good night's sleep and wake up feeling refreshed and ready for another day of music and fun.
    Located within the festival grounds, our tents are just a short walk away from all the stages and attractions. You won't have to worry about transportation or navigating crowds to get to the festival - you'll be right in the heart of it all.
    Our tents also come with a range of amenities to make your stay even more comfortable. You'll have access to clean restroom facilities, hot showers, and charging stations for your devices. We also have a dedicated staff available to assist with any needs or questions you may have during your stay.
    But the best part of our tent accommodation packages is the community. You'll be surrounded by other festival-goers who are just as excited as you are to be a part of the experience. You'll make new friends, share stories, and create memories that will last a lifetime.
    Don't miss out on this opportunity to enhance your music festival experience. Book your tent accommodation package today and get ready for an unforgettable adventure. We can't wait to see you there!
    "
    />
</main>

<Footer />

<style>
    main {
        background-color: #f6e9ff;
        /* display: flex; */
    }

    /* .text {
        width: 700px;
        margin: 20px 40px;
    }
     */
    .header {
        display: flex;
        flex-direction: row;
        border: 1px;
        border-color: #9468cf;
    }
</style>

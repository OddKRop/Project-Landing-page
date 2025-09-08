<script>
    import {FaqItem, Button} from "$components";
    import twitterIcon from "$assets/twitter.webp";
</script>

<section class="landing-page-section">
    <h2 class="mb-l">Frequently asked questions</h2>
    <div class="faq-container">
        <FaqItem />
    </div>
    <div class="additional-info">
        <Button class="mt-s">BUY NOW</Button>
        <p class="mt-m">Any other questions?<p>
        <p>
            Hit me up on twitter <img src={twitterIcon} class="twitter-icon" alt="" />
        </p>
    </div>
</section>
<script>
    //logic
    import imgFoodTracking from '$lib/images/fooddiary.jpg';
    import mockup from '$lib/images/nutricoach mockup.png';
    import CameraIcon from 'svelte-icons/go/GoDeviceCamera.svelte';
    import JournalIcon from 'svelte-icons/io/IoMdJournal.svelte';
    import ShareIcon from 'svelte-icons/fa/FaShareAltSquare.svelte';
</script>

<svelte:head>
    <title>Home</title>
    <meta name="description"content="nutricoach homepage">
</svelte:head>

<main>
    <!-- welcome to nutricoach -->
    <div class="container-fluid">
        <div class="row" id="firstRow">
            <div class="container col-xxl-8 px-4 py-5">
                <div class="row flex-lg-row-reverse align-items-center g-5 py-5">
                  <div class="col-10 col-sm-8 col-lg-6">
                    <img src={mockup} class="d-block mx-lg-auto img-fluid" alt="Bootstrap Themes" width="700" height="500" loading="lazy">
                  </div>
                  <div class="col-lg-6">
                    <h1 class="display-5 fw-semibold text-body-emphasis lh-1 mb-3">Welcome to <strong>Nutricoach</strong></h1>
                    <p class="lead">Revolutionize the way you track your nutrtion with Nutricoach: your new food companion. No more tedious typing and searching— just snap a picture with your phone, and we will handle the rest.</p>
                    <div class="d-grid gap-2 d-md-flex justify-content-md-start">
                      <a href="user\signup" type="button" class="btn btn-primary btn-lg px-4 me-md-2">Let's Get Started</a>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <!-- nutricoach features -->
    <div class="container-fluid">
        <div class="container px-4 py-5" id="featured-3">
            <h2 class="pb-2 border-bottom">Features</h2>
            <div class="row g-4 py-5 row-cols-1 row-cols-lg-3">
              <div class="feature col">
                <div class="feature-icon d-inline-flex align-items-center justify-content-center bg-gradient fs-2 mb-3">
                  <svg class="icon" width="1.5em" height="1.5em" style="color: 6748ff;"><CameraIcon /></svg>
                </div>
                <h3 class="fs-2 text-body-emphasis">Snap</h3>
                <p>Paragraph of text beneath the heading to explain the heading. We'll add onto it with another sentence and probably just keep going until we run out of words.</p>
              </div>
              <div class="feature col">
                <div class="feature-icon d-inline-flex align-items-center justify-content-center bg-gradient fs-2 mb-3">
                    <svg class="icon" width="1.5em" height="1.5em" style="color: 6748ff;"><JournalIcon /></svg>
                </div>
                <h3 class="fs-2 text-body-emphasis">Log</h3>
                <p>Paragraph of text beneath the heading to explain the heading. We'll add onto it with another sentence and probably just keep going until we run out of words.</p>
              </div>
              <div class="feature col">
                <div class="feature-icon d-inline-flex align-items-center justify-content-center bg-gradient fs-2 mb-3">
                    <svg class="icon" width="1.5em" height="1.5em" style="color: 6748ff;"><ShareIcon /></svg>
                </div>
                <h3 class="fs-2 text-body-emphasis">Share</h3>
                <p>Paragraph of text beneath the heading to explain the heading. We'll add onto it with another sentence and probably just keep going until we run out of words.</p>
              </div>
            </div>
          </div>
    </div>
</main>

<style>
    #firstRow{
        background: linear-gradient(to right, #9681ff, hsl(0, 0%, 91%));
    }
    img{
        height:auto;
        width:auto;
    }
    .btn{
        background-color: #6748ff;
        color: #ffffff;
    }
    /*styles*/
</style>
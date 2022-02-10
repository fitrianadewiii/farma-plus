<template>
  <section>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <link href='https://fonts.googleapis.com/css?family=Nunito Sans' rel='stylesheet'>
    <Navbar />
    <div class="container mt-3 mb-5">
      <router-view />
    </div>
  </section>
</template>

<script>
  import Navbar from './../components/Navbar'

  export default {
    components: {
      Navbar
    }
  }

</script>
<style>
  body {
    font-family: 'Nunito Sans';
  }

  .card {
    position: relative;
    display: flex;
    flex-direction: column;
    min-width: 0;
    word-wrap: break-word;
    background-color: #fff;
    background-clip: border-box;
    /* border: 1px solid rgba(0, 0, 0, 0.125); */
    border-radius: 8px;
    box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
  }

  .p {
    color: #6A6767
  }

  .font{
    color:#6A6767
  }
  .h1.h2.h3.h4.h5.h6{
    color:#6A6767
  }

  /*Set the row height to the viewport*/
  .row-height {
    height: 100vh;
  }

  /*Set up the columns with a 100% height, body color and overflow scroll*/

  .left {
    height: 100%;
    overflow-y: scroll;
  }



  /*Remove the scrollbar from Chrome, Safari, Edge and IE*/
  ::-webkit-scrollbar {
    width: 0px;
    background: transparent;
  }

  * {
    -ms-overflow-style: none !important;
  }

</style>

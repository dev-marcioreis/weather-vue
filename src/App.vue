<script>

  export default {
    name: 'app',
    data () {
      return {
        api_key: 'd434f4c9ad064a905d8c5cd65770facf'
      }
    }
  } 

</script>

<template>

    <div id="app">
      <main>
        <div class="search-box">
          <input type="text" class="search-bar" placeholder="Cidade..." />
        </div>
        <div class="wrap">
          <div class="location-content">
            <div class="location">São Paulo, BR</div>
            <div class="date">Hoje</div>
          </div>
          <div class="weather-box">
            <div class="temperature">21ºc</div>
            <div class="weather">Chovendo</div>
          </div>
        </div>
      </main>
    </div>

</template>


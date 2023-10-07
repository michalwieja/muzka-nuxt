<template>
  <div class="music-theraphy">
    <div class="wrapper">
      <div class="left">
        <div class="slogan">
          MuzKa to pierwsze miejsce, gdzie jest prowadzona profesjonalna muzykoterapia indywidualna i grupowa dla różnych
          grup wiekowych
        </div>
        <div class="text">
          Główną ideą MuzKi jest rozwój każdego człowieka nie tylko pod względem muzycznym. Poprzez muzykoterapię
          pracujemy nad rozwojem społecznym, emocjonalnym, komunikacyjnym, poznawczym oraz ruchowym
        </div>
        <div>
          <NuxtLink to="/muzykoterapia">
            <Button label="Co to jest muzykoterapia?"></Button>
          </NuxtLink>
        </div>
      </div>
      <div class="right">
        <div class="title">
          Proces muzykoterapii w <span>MuzCe</span> jest:
        </div>
        <ul class="list">
          <li>
            dostosowany indywidualnie do każdego uczestnika terapii
          </li>
          <li>
            proces ten jest zaplanowany
          </li>
          <li>
            podlega standardom Światowej Federacji Muzykoterapeutów
          </li>
          <li>
            jest on monitorowany, tzn. terapeuci analizują przebieg procesu, realizując wyznaczone cele terapeutyczne oraz
            podlegając superwizji
          </li>
        </ul>
      </div>
    </div>

  </div>
</template>

<script>
export default {
  name: 'MusicTheraphy',
}
</script>

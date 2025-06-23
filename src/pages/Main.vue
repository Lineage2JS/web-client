<template>
  <div>
    <h1>Enter the World of Lineage 2</h1>
    <div>Подпись для заголовка</div>
    <div class="mt-3">
      <button class="btn btn-primary mr-3 pt-2 pb-2 pr-4 pl-4">Download</button>
      <button class="btn btn-success pt-2 pb-2 pr-4 pl-4">Start game</button>
    </div>

    <hr>

    <h3>Server status</h3>
    <b-card-group deck>
      <b-card>Server status</b-card>
      <b-card>Players online</b-card>
      <b-card>Server info</b-card>
    </b-card-group>

    <hr>

    <h3>Download & Updates</h3>
    <b-card-group deck>
      <b-card>
        Game client
        <br>
        <button class="btn btn-primary mr-3 pt-2 pb-2 pr-4 pl-4">Download</button>
      </b-card>
      <b-card>
        Patch
        <br>
        <button class="btn btn-primary mr-3 pt-2 pb-2 pr-4 pl-4">Download</button>
      </b-card>
    </b-card-group>
  </div>
</template>

<script>
import { Vue, Component } from 'vue-property-decorator';

@Component({})
export default class Main extends Vue {
  
}
</script>
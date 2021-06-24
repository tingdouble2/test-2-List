<template>
  <center class="pt-12">
    <v-card width="400px">
      <v-row>
        <v-col> {{ firstname }} </v-col>
        <v-col> {{ lastname }} </v-col>
        <v-col> {{ age }} </v-col>
      </v-row>
      <div v-for="list in employees" :key="list.index">
        <v-row>
          <v-col>
            {{ list.name }}
          </v-col>
          <v-col>
            {{ list.lastname }}
          </v-col>
          <v-col>
            {{ list.age }}
          </v-col>
        </v-row>
      </div>
    </v-card>
  </center>
</template>
<script>
export default {
  data () {
    return {
      employees: [
        {
          name: 'Wanwisa',
          lastname: 'Sawatdee',
          age: 20
        },
        {
          name: 'Panee',
          lastname: 'Tawan',
          age: 35
        },
        {
          name: 'Nuttanan',
          lastname: 'Koonmin',
          age: 29
        },
        {
          name: 'Janjao',
          lastname: 'kKhondon',
          age: 25
        },
        {
          name: 'Phumjai',
          lastname: 'Fahkam',
          age: 33
        },
        {
          name: 'attama',
          lastname: 'polawat',
          age: 30
        },
        {
          name: 'Wanrun',
          lastname: 'Sasisan',
          age: 29
        },
        {
          name: 'Panuwat',
          lastname: 'Nuntita',
          age: 34
        },
        {
          name: 'Ponlawat',
          lastname: 'Khawjarern',
          age: 28
        },
        {
          name: 'Sawatdee',
          lastname: 'Lowata',
          age: 23
        },
        {
          name: 'Adisorn',
          lastname: 'Pornsawan',
          age: 30
        },
        {
          name: 'Bina',
          lastname: 'Sara',
          age: 25
        },
        {
          name: 'Mullika',
          lastname: 'Puwadit',
          age: 20
        },
        {
          name: 'Apichaya',
          lastname: 'Ponsawan',
          age: 33
        },
        {
          name: 'Nuthapong',
          lastname: 'Ponpom',
          age: 26
        },
        {
          name: 'Adithep',
          lastname: 'Pongpun',
          age: 28
        },
        {
          name: 'Namwan',
          lastname: 'Nita',
          age: 34
        },
        {
          name: 'Woradech',
          lastname: 'Apinihan',
          age: 29
        }
      ],
      firstname: 'ชื่อ',
      lastname: 'นามสกุล',
      age: 'อายุ'
    }
  }
}
</script>

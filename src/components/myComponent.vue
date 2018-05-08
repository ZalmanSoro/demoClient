<template>
  <v-layout>
      
    <v-flex xs12 sm6 offset-sm3>
           <v-card>
          <v-card-title>
              <div>
            <h1 class="headline mb-0">דבורושקה אהובתי</h1>
            <h1 class="headline mb-0">מוקדש באהבה</h1>
          </div>
          </v-card-title>
        </v-card>
      <v-card>
       <a href="https://www.youtube.com/watch?v=p7zf_3q8bMg" width="700">
        <v-card-media src='https://www.zimmer.co.il/hipo/%D7%AA%D7%9E%D7%95%D7%A0%D7%94%20455.jpg' height="200px">
        </v-card-media></a>
        <v-card-title primary-title>
          <div>
            <h3 class="headline mb-0">הליכה לקיסריה</h3>
            <div>....הרוח והחושך והמים</div>
          </div>
        </v-card-title>
        <!-- <v-card-actions>
          <v-btn flat color="orange">Share</v-btn>
          <v-btn flat color="orange">Explore</v-btn>
        </v-card-actions> -->
      </v-card>
    
    </v-flex>
    
  </v-layout>
</template>

<script>

export default {
  name: 'myComponent',
 
  props: {
  }
}
</script>

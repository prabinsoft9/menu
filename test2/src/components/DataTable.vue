<template>
    <v-app>
    <v-container class="mt-5">
      <v-card>
        <v-card-title>
          {{DatatableName}}
          <v-spacer></v-spacer>
          <v-text-field
            v-model="search"
            append-icon="mdi-magnify"
            label="Search"
            single-line
            hide-details
          ></v-text-field>
        </v-card-title>
        <v-data-table 
          :headers="headers"
          :items="employe"
          :search="search"
          :items-per-page="5"
        >

      
    </v-data-table>
    <v-data-table
          :headers="headers"
          :items="employe"
          :search="search"
          :items-per-page="5"
        >
      
    </v-data-table>
      </v-card>
      </v-container>
    </v-app>
  </template>
  <script>
  export default {
    

    data: () => ({
      search: '',
      DatatableName:'Hello',
      props: {
      Datatablename: String,
      },
      employe: [
        {
          name: 'Prabin Karki',
          address: 'Imadol',
          phoneNumber: '9860993927',
          age: 24,
          job_type: 'Web Development',
          department: 'Development',
          location:'hello'
        },
        {
          name: 'Prabin Karki',
          address: 'Imadol',
          phoneNumber: '9860993927',
          age: 24,
          job_type: 'Web Development',
          department: 'Development',
          location:'hello'
        },
        {
          name: 'Prabin Karki',
          address: 'Imadol',
          phoneNumber: '9860993927',
          age: 24,
          job_type: 'Web Development',
          department: 'Development',
          location:'hello'
        },
        {
          name: 'Prabin Karki',
          address: 'Imadol',
          phoneNumber: '9860993927',
          age: 24,
          job_type: 'Web Development',
          department: 'Development',
          location:'hello'
        },
        {
          name: 'Prabin Karki',
          address: 'Imadol',
          phoneNumber: '9860993927',
          age: 24,
          job_type: 'Web Development',
          department: 'Development',
          location:'hello'
        },
        {
          name: 'Prabin Karki',
          address: 'Imadol',
          phoneNumber: '9860993927',
          age: 24,
          job_type: 'Web Development',
          department: 'Development',
          location:'hello'
        },
        {
          name: 'Prabin Karki',
          address: 'Imadol',
          phoneNumber: '9860993927',
          age: 24,
          job_type: 'Web Development',
          department: 'Development',
          location:'hello'
        },
        {
          name: 'Prabin Karki',
          address: 'Imadol',
          phoneNumber: '9860993927',
          age: 24,
          job_type: 'Web Development',
          department: 'Development',
          location:'hello'
        },
        {
          name: 'Prabin Karki',
          address: 'Imadol',
          phoneNumber: '9860993927',
          age: 24,
          job_type: 'Web Development',
          department: 'Development',
          location:'hello'
        },
        {
          name: 'Prabin Karki',
          address: 'Imadol',
          phoneNumber: '9860993927',
          age: 24,
          job_type: 'Web Development',
          department: 'Development',
          location:'hello'
        },
        {
          name: 'Prabin Karki',
          address: 'Imadol',
          phoneNumber: '9860993927',
          age: 24,
          job_type: 'Web Development',
          department: 'Development',
          location:'hello'
        },
        {
          name: 'Prabin Karki',
          address: 'Imadol',
          phoneNumber: '9860993927',
          age: 24,
          job_type: 'Web Development',
          department: 'Development',
          location:'hello'
        },
        {
          name: 'Prabin Karki',
          address: 'Imadol',
          phoneNumber: '9860993927',
          age: 24,
          job_type: 'Web Development',
          department: 'Development',
          location:'hello'
        },
        

      ],
      headers: [
        {
          text: 'Name of Employee',
          align: 'start',
          sortable: false,
          value: 'name',
          
        },
        { text: 'Address', value: 'address' },
        { text: 'Phone Number', value: 'phoneNumber' },
        { text: 'Age', value: 'age' },
        { text: 'Designation', value: 'job_type' },
        { text: 'Department', value: 'department' },
        { text: 'Department', value: 'department' },
        { text: 'Department', value: 'department' },
        { text: 'Department', value: 'department' },
        { text: 'Department', value: 'department' },
        { text: 'Department', value: 'department' },
        { text: 'Department', value: 'department' },
        { text: 'Department', value: 'department' },  
        { text: 'Location', value: 'location' },
        { text: 'Iron (%)', value: 'iron' },
        { text: 'Iron (%)', value: 'iron' },
        { text: 'Place', value: 'place' }
      ],
    }),
  };
  </script>

  <style >
    
     tr > td:nth-child(1) {
      background: #fff;
      position: sticky;
      left: 0;

    }
    tr > td:nth-child(2) {
      background: #fff;
      position: sticky;
      left: 85px;
      overflow: hidden;
    }
    tr > td:nth-child(3) {
      background: #fff;
      position: sticky;
      left: 160px;
      overflow-x: hidden;
    }
    tr > th:nth-child(1) {
      background: #fff;
      position: sticky;
      left: 0;
    }
    tr > th:nth-child(2) {
      background: #fff;
      position: absolute;
      margin-top: 7px;
      left: 85px;
      overflow-x: hidden;
    }
    tr > th:nth-child(3) {
      background: #fff;
      position: sticky;
      left: 160px;
      overflow-x: hidden;
    
    }
    
    
  </style>
<template>
  <div>
    <v-container>
      <h4>Created By</h4>
     <!-- <v-list-item>
          <v-list-item-avatar height="100px" width="100px">
              <v-img src="img/irfan.jpg" ></v-img>
          </v-list-item-avatar>
          <v-list-item-content>
              <v-list-item-title>Nama</v-list-item-title>
              <v-list-item-subtitle>Mohamad Irfan</v-list-item-subtitle>
              <v-divider></v-divider>
              <v-list-item-title>Tempat, Tanggal Lahir</v-list-item-title>
              <v-list-item-subtitle>Bandung, 13 Juni 1997</v-list-item-subtitle>
              <v-divider></v-divider>
              <v-list-item-title>Alamat</v-list-item-title>
              <v-list-item-subtitle>Cilame, Bandung Barat</v-list-item-subtitle>
              <v-divider></v-divider>
              <v-list-item-title>Hobi</v-list-item-title>
              <v-list-item-subtitle>Melihara Ikan</v-list-item-subtitle>
          </v-list-item-content>
      </v-list-item>
      <v-list-item>
          <v-list-item-content>
              <v-list-item-title>Nama</v-list-item-title>
              <v-list-item-subtitle>Iqbal Septiadi Tawakal</v-list-item-subtitle>
              <v-divider></v-divider>
              <v-list-item-title>Tempat, Tanggal Lahir </v-list-item-title>
              <v-list-item-subtitle>Bandung, 28 September 1997</v-list-item-subtitle>
              <v-divider></v-divider>
              <v-list-item-title>Alamat</v-list-item-title>
              <v-list-item-subtitle>Cikalong, Bandung barat</v-list-item-subtitle>
              <v-divider></v-divider>
              <v-list-item-title>Hobi</v-list-item-title>
              <v-list-item-subtitle>Futsal,Badminton</v-list-item-subtitle>
          </v-list-item-content>
          <v-list-item-avatar height="100px" width="100px">
              <v-img src="img/iqbal.jpg" ></v-img>
          </v-list-item-avatar>
      </v-list-item> -->
      <v-card flat>
        <v-img src="img/irfan.jpg" height="350px" width="100%"></v-img>
        <v-container>
            <v-simple-table>
                <tbody>
                    <tr>
                        <th>Nama</th>
                        <td>Mohamad Irfan</td>
                    </tr>
                    <tr>
                        <th>Tempat, Tanggal Lahir</th>
                        <td>13 Juni 1997</td>
                    </tr>
                    <tr>
                        <th>Alamat</th>
                        <td>Cilame GBR 1f5 no 12 a, Ngamprah, Bandung Barat</td>
                    </tr>
                </tbody>
            </v-simple-table>
        </v-container>
      </v-card> 
       <v-card flat>
        <v-img src="img/iqbal.jpg" height="350px" width="100%"></v-img>
        <v-container>
            <v-simple-table>
                <tbody>
                    <tr>
                        <th>Nama</th>
                        <td>Iqbal Septiadi Tawakal</td>
                    </tr>
                    <tr>
                        <th>Tempat, Tanggal Lahir</th>
                        <td>28 September 1997</td>
                    </tr>
                    <tr>
                        <th>Alamat</th>
                        <td>Cikalong Wetan, Cikalong, Bandung Barat</td>
                    </tr>
                </tbody>
            </v-simple-table>
        </v-container>
      </v-card> 
    </v-container>
  </div>
</template>

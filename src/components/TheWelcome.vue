<script setup lang="ts">
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
</script>

<template>
 <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Tentang Saya</template>
    Saat ini, saya tengah menempuh pendidikan sebagai mahasiswa di <a href="https://uir.ac.id/" target="_blank" rel="noopener">Universitas Islam Riau</a>, yang berlokasi di Jalan Kaharuddin Nst, Pekanbaru. Sedang berada di semester 4, saya mengambil jurusan Teknik Informatika di institusi tersebut.
    Sebelumnya, saya bersekolah di Sekolah Menengah Atas
    <a href="https://sman1siak.sch.id/" target="_blank" rel="noopener">SMAN 1 Siak</a>
    Saya Tinggal Di Paret Baru, Desa langkai Kec. Siak Kabupaten Siak Provinsi Riau
  </WelcomeItem>
  <hr />

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Sekilas Tentang TI</template>
Saya mengambil Program didik Teknik Informatika (S1) karena saya teratarik untuk mempelajari Teknologi
Saya masuk di kelas A angkatan 2022 yang biasa disebut DoblehA22, di kelas ini saya banyak mendapatkan teman baik
yang ingin belajar serta berkembang.
  

    <br />

  </WelcomeItem>
  <hr/>
  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Hobi</template>
    <li>Futsal</li>
    <li>Renang</li>
    <li>Catur</li>
    <li>Badminton</li>
    <li>PUBG</li>
      
  </WelcomeItem>
  <hr />
  <WelcomeItem>
    <template #icon>
    
      <ToolingIcon />
    </template>
    <template #heading>Skill</template>
<ul>
   <li> 1. Problem Solving </li>
  <li> 2. Time Management</li>
<li> 3. C++ </li>
<li> 4. CSS </li>
<li> 5. HTML </li>
  </ul>
  </WelcomeItem>
  <hr />
  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Contact Person</template>

    Email: zhorifmuflih@student.uir.ac.id <br>
    Instagram : <a href="zhorifmflh" target="_blank">@zhorifmflh </a
    > <br>
    WhatsApp : +6221-7082-1020***
    
  </WelcomeItem>
</template>

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
    Saya Syahrul Ramadhan dan saya merupakan mahasiswa di kampus universitas islam riau yang terletak di jalan Kaharuddin Nst
    Pekanbaru. Sekarang Saya sedang menajalankan pendidikan yang duduk di semester 4 jurusan Teknik Informatika Universitas Islam Riau.
    Saya Berasal dari Perawang Kab.Siak, Kec.Tualang ,Provinsi Riau
  </WelcomeItem>
  <hr />
  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Pendidikan</template>

    SDS  YPPI TUALANG 2010-2016<br />
    SMPS YPPI TUALANG 2016-2019<br />
    SMKS YPPI TUALANG 2019-2022<br />
    UNIVERSITAS ISLAM RIAU 2022-NOW
  </WelcomeItem>
  <hr />
  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Pengalaman</template>
    Saya Pernah melakukan Praktik Kerja Lapangan atau Magang di PT. 2K123 (WanXP)
    <ul>
      <li>Memasang wifi menggunakan kabel fiber optik</li>
      <li>Meperbaiki arus jaringan yang putus</li>
      <li>Menyeting Access point</li>
      <li>Melakukan troubleshoot di lapangan yang ada di lapangan</li>
      <li>Pemasangan Radio pada tower</li>
    </ul>
  </WelcomeItem>
  <hr />
  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Skill</template>
    <ul>
      <li>Pemasangan jaringan komputer</li>
      <li>IoT(Internet Of Things)</li>
      <li>HTML</li>
      <li>PHP</li>
      <li>C++</li>
    </ul>
  </WelcomeItem>
  <hr />
  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Hubungi Saya</template>

    Instagram :<a href="https://www.instagram.com/syhrull.e?igsh=MTAwb2F2M3V5ZmF3aw==" target="_blank">syhrull.e </a
    ><br />
    Email : syhrulramadhan511@gmail.com<br />
    NPM   : 223510458
    No HP : +62 887-0823-9531
  </WelcomeItem>
</template>
<script setup>
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
    <template #heading> Nama</template>

  
    <a href="https://vuejs.org/" target="_blank" rel="noopener"></a>
    Miftahul Jannah
  </WelcomeItem>

  <WelcomeItem style="text-align: justify;">
  <template #icon>
    <ToolingIcon />
  </template>
  <template #heading>Tentang Saya</template>

  Sebagai mahasiswa Teknik Informatika dengan minat yang mendalam dalam analisis data dan pengembangan perangkat lunak, saya memiliki pemahaman yang kuat tentang konsep-konsep fundamental dalam ilmu komputer dan keterampilan teknis yang kokoh. Saya memiliki keahlian dalam pengolahan dan analisis data, serta kemampuan dalam merancang dan mengimplementasikan solusi perangkat lunak yang efisien dan dapat diandalkan. Saya memiliki tekad yang kuat untuk terus belajar dan berkembang dalam bidang analisis data dan pemrograman, dan saya siap untuk memberikan kontribusi yang signifikan dalam proyek-proyek yang melibatkan teknologi informasi.
</WelcomeItem>


  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Pendidikan</template>

    S1 - Teknik Informatika,
    <a href="https://pinia.vuejs.org/" target="_blank" rel="noopener"> Universitas Islam Riau </a>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Keterampilan</template>
    <div>
    <ul>
      <li>Microsoft Word, Power Point  dan Excel.</li>
      <li>Adobe Photoshop</li>
      <li>MySQL</li>
    </ul>
  </div>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Penghargaan</template>
  <div>
    <ul>
      <li>Sertifikat Keahlian Teknik Komputer & Jaringan, Tahun 2022</li>
      <li>Beasiswa Pemprov Prestasi S1 Tahun 2022</li>
    </ul>
  </div>
  </WelcomeItem>
</template>

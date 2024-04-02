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
    <template #heading>Riwayat Pendidikan</template>

    <a href="https://vuejs.org/" target="_blank" rel="noopener"></a>

    *SDN 015 Tandun, Rokan Hulu(2009-2012) <br />
    *SDN 009 Tandun, Rokan Hulu(2012-2015) <br />
    *SMPN 2 Tandun, Rokan Hulu(2015-2018) <br />
    *SMAN 2 Tandun, Rokan Hulu(2018-2021)
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>keterampilan</template>
    *Keterampilan Komunikasi <br />
    *Keterampilan Analisis data <br />
    *Keterampilan Manajemen Waktu
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Pengalaman kerja</template>
    Asisten Peneliti <br />
    ABC Institute for Research, Bandung, Indonesia <br />
    Juni 2018 - Desember 2019 <br />

    *Mendukung penelitian di bidang biologi molekuler dengan mengumpulkan dan menganalisis data
    eksperimental. <br />
    *Bertanggung jawab untuk memelihara stok dan kultur sel, serta melakukan percobaan laboratorium
    sesuai dengan protokol penelitian. <br />
    *Berkontribusi dalam penulisan laporan penelitian dan makalah ilmiah untuk publikasi jurnal.
    <br />
    *Mengkoordinasikan kolaborasi dengan universitas dan lembaga penelitian lainnya untuk pertukaran
    data dan sumber daya.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Media Sosial</template>
    Instagram : @fajarfrd
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Kontak</template>
    fajarferdianda@gmail.com/082211901261
  </WelcomeItem>
</template>

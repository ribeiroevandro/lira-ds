---
layout: page
title: Conheça o time
description: The development of Vite is guided by an international team.

sidebar: false
---

<script setup>
  import {
  VPTeamPage,
  VPTeamPageTitle,
  VPTeamMembers,
  VPTeamPageSection
} from 'vitepress/theme'
import { teamMembers } from './_data/contributors'
</script>

<VPTeamPage>
  <VPTeamPageTitle>
    <template #title>Conheça o time</template>
    <template #lead>
      O desenvolvimento do Vega Checkout é liderado por uma equipe remota, alguns dos quais escolheram ser apresentados abaixo.
    </template>
  </VPTeamPageTitle>
  <VPTeamMembers size="small" :members="teamMembers" />
</VPTeamPage>
<template>
  <div>
    <v-list flat subheader>

      <v-list-item-group v-model="settings" multiple active-class="">

        <Tarefa />

      </v-list-item-group>
    </v-list>
  </div>
</template>

<script>
import Tarefa from "../components/tarefas/Tarefa"
export default {
  name: 'v-Home',
  components: {
    Tarefa
  },
}
</script>

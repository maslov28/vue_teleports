<template>
  <div>
    <h1>Телепорты</h1>
    <ul>
      <li>В точке входа приложения добавить div с идентификатором modal</li>
      <li>Создать компонент modal-window, который будет появляться в месте расположения #modal</li>
    </ul>
  </div>
  <teleport to="#modal">
    <modal-window></modal-window>
  </teleport>
</template>

<script>
import ModalWindow from './components/ModalWindow.vue'
export default {
  components: {
    ModalWindow
  }
}
</script>
<template>
  <div class="services">
    <Service
      title="Front end"
      description="Nele definimos que o ESLint deve estender as configurações recomendadas do prettier, registrar o plugin Prettier que nós instalamos no começo do tutorial e exibir os erros do Prettier como errors."
    />
    <Service
      title="Back end"
      description="Com isso, definimos que nosso código terá uma identação em que a tecla tab equivale a 2 espaços, usaremos aspas simples e não aspas duplas e que no fim de cada linha deve ser adicionado um ponto e vírgula."
    />
    <Service
      title="Manutenção"
      description="Se você tiver algum problema, comece por tentar reiniciar o VSCode… A instalação do plugins pode ainda não ter sido entendida por ele corretamente."
    />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { Service } from '@/components/molecules'

export default defineComponent({
  components: { Service }
})
</script>

<style lang="scss" scoped>
.services {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  grid-gap: 5rem;
}
</style>

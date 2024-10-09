<script setup lang="ts">
import {
  Card,
  CardContent,
  CardDescription,
  CardFooter,
  CardHeader,
  CardTitle,
} from "./ui/card";
import { Slider } from "./ui/slider";
</script>

<template>
  <Card class="bg-card max-w-[40rem]">
    <CardHeader>
      <CardTitle> Título da Carta </CardTitle>
      <CardDescription class="ml-[2px]"> Descrição da carta </CardDescription>
    </CardHeader>

    <CardContent>
      Lorem ipsum, dolor sit amet consectetur adipisicing elit. Odio laborum
      temporibus ipsa excepturi alias praesentium iure voluptatum perspiciatis
      inventore assumenda sunt sit quidem ullam, rem consequatur. Commodi est
      repudiandae ducimus?
    </CardContent>

    <CardFooter class="flex-col gap-2">
      Grau de Dificuldade na Matéria
      <Slider class="max-w-[50%]" :default-value="[25]" :max="100" :step="25" />
    </CardFooter>
  </Card>
</template>

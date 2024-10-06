<script setup lang="ts">
import {
  Card,
  CardContent,
  CardDescription,
  CardTitle,
  CardHeader,
  CardFooter,
} from "./components/ui/card";
</script>

<template>
  <div class="flex justify-center mt-10">
    <Card class="bg-background max-w-[40rem]">
      <CardHeader>
        <CardTitle> Título da Carta </CardTitle>
        <CardDescription class="ml-[2px]"> Descrição da carta </CardDescription>
      </CardHeader>
      <CardContent>
        Lorem ipsum, dolor sit amet consectetur adipisicing elit. Odio laborum
        temporibus ipsa excepturi alias praesentium iure voluptatum perspiciatis
        inventore assumenda sunt sit quidem ullam, rem consequatur. Commodi est
        repudiandae ducimus?</CardContent
      >
      <CardFooter> footer da carta </CardFooter>
    </Card>
  </div>
</template>

<style scoped></style>

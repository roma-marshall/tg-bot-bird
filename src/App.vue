<template>
  <div>
  </div>
</template>

<script setup>
import { Bot } from 'grammy'

console.log(import.meta.env.VITE_API_KEY)
console.log(process.env.VITE_API_KEY)


// const bot = new Bot(import.meta.env.VITE_API_KEY)

// const bot = new Bot(process.env.API_KEY)
//
// bot.command('start', (ctx) => ctx.reply('Welcome! Up and running.'))
// bot.on('message', (ctx) => ctx.reply('Got another message!'))
//
// bot.start()
</script>
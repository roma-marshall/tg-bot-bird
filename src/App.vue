<template>
  <div>
  </div>
</template>

<script setup>
import { Bot } from 'grammy'

console.log(process.env.VERCEL_ENV_VAR)


// const bot = new Bot(import.meta.env.VITE_API_KEY)

// const bot = new Bot(process.env.API_KEY)
//
// bot.command('start', (ctx) => ctx.reply('Welcome! Up and running.'))
// bot.on('message', (ctx) => ctx.reply('Got another message!'))
//
// bot.start()
</script>
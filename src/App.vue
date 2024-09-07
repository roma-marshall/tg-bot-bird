<template>
  <div>
  </div>
</template>

<script setup>
import { Bot } from 'grammy'

// const api_key = import.meta.env.VITE_API_KEY
const api_key = process.env.VITE_API_KEY


console.log(api_key)

// const bot = new Bot(api_key)
//
// bot.command('start', (ctx) => ctx.reply('Welcome! Up and running.'))
// bot.on('message', (ctx) => ctx.reply('Got another message!'))
//
// bot.start()
</script>
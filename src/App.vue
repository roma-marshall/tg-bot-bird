<template>
  <div>
  </div>
</template>

<script setup>
import { Bot } from 'grammy'

const bot = new Bot(import.meta.env.VITE_API_KEY)

bot.command('start', (ctx) => ctx.reply('Welcome! Up and running.'))
bot.on('message', (ctx) => ctx.reply('Got another message!'))

bot.start()
</script>
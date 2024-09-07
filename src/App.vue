<template>
  <div>
  </div>
</template>

<script setup>
import { Bot } from 'grammy'

// const api_key = import.meta.env.VITE_API_KEY // local
const api_key = process.env.VITE_API_KEY // vercel

const bot = new Bot(api_key, {
  headers: {
    'Access-Control-Allow-Origin': '*',
    'Content-Type': 'application/json',
  }
})

bot.command('start', async (ctx) => {
  await ctx.reply('Welcome to Flappy Bird! 🎉🎉🎉\n' +
      '\n' +
      'Play a decentralized web3 decentralized Telegram game here, with the old all familiar classic gameplay. We have a unique vision to launch new Telegram Mini Apps.\n' +
      '\n' +
      'Start playing now and who knows what cool stuff you might find! 🚀\n' +
      '\n' +
      'Stay with Flappy Bird! 🌟')
})

// bot.on('message', (ctx) => ctx.reply('Got another message!'))

bot.start()
</script>
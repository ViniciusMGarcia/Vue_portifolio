<template>
  <section class="p-8 max-w-md mx-auto">
    <h2 class="text-2xl font-bold mb-4">Entre em contato</h2>

    <form class="flex flex-col gap-4">
      <input type="text" placeholder="Seu nome" class="p-2 border rounded" />
      <input type="email" placeholder="Seu e‑mail" class="p-2 border rounded" />
      <textarea
        placeholder="Sua mensagem"
        class="p-2 border rounded h-32"
      ></textarea>

      <button type="button" class="bg-blue-600 text-white p-2 rounded">
        Enviar
      </button>
    </form>

    <div class="mt-6 flex justify-center gap-6">
      <a href="https://www.linkedin.com/in/vinicius-garcia-4b35721b8" target=" LinkedIn" class="text-blue-500 hover:underline">
        LinkedIn
      </a>
      <a href="https://github.com/ViniciusMGarcia" target=" GitHub" class="text-gray-900 hover:underline">
        GitHub
      </a>
    </div>
  </section>
</template>

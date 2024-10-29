<script setup></script>

<template>
  <!-- <div class="text-2xl font-light text-[#4d4d4d] w-screen h-screen mx-5 my-10">
    <h1 class="text-3xl font-bold font-sans">todos</h1>

    <div class="todoapp__content">
      <header class="todoapp__header">
        <button class="todoapp__toggle-all active"></button>
        <form>
          <input
            type="text"
            class="todoapp__new-todo"
            placeholder="What needs to be done?"
          />
        </form>
      </header>

      <section class="todoapp__main">
        <div class="todo completed">
          <label class="todo__status-label">
            <input type="checkbox" class="todo__status" checked />
          </label>

          <form>
            <input
              type="text"
              class="todo__title-field"
              placeholder="Empty todo will be deleted"
              value="Todo is being edited now"
            />
          </form>
          <span class="todo__title"></span>
          <button class="todo__remove">x</button>

          <div class="modal overlay">
            <div class="modal-background has-background-white-ter"></div>
            <div class="loader"></div>
          </div>
        </div>
      </section>
    </div>
  </div> -->

  <div class="text-2xl font-light text-gray-600 w-screen h-screen mx-5 my-10">
    <h1 class="text-3xl font-bold font-sans">todos</h1>

    <div class="bg-white shadow-lg rounded-lg p-5">
      <header class="flex items-center space-x-2 mb-4">
        <button class="bg-blue-500 text-white p-2 rounded-full"></button>
        <form>
          <input
            type="text"
            class="w-full p-2 border border-gray-300 rounded-md"
            placeholder="What needs to be done?"
          />
        </form>
      </header>

      <section class="space-y-4">
        <div class="flex items-center space-x-2">
          <label class="">
            <input type="checkbox" class="" checked />
          </label>

          <form>
            <input
              type="text"
              class="p-2 border border-gray-300 rounded-md"
              placeholder="Empty todo will be deleted"
              value="Todo is being edited now"
            />
          </form>
          <span class=""></span>
          <button class="text-red-500 font-bold">x</button>
          <p></p>

          <button>submit</button>

          <!-- <div class="fixed inset-0 flex items-center justify-center">
            <div
              class="has-background-white-ter absolute inset-0 bg-white opacity-75"
            ></div>
            <div
              class="border-t-4 border-blue-500 rounded-full w-10 h-10 animate-spin"
            ></div>
          </div> -->
        </div>
      </section>
    </div>
  </div>
</template>

<style lang="scss"></style>

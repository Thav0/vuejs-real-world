<template>
  <div id="nav">
    <router-link to="/">Real World Element</router-link> |
    <nav>
      <router-link :to="{ name: 'event-list' }">Home</router-link> |
      <router-link :to="{ name: 'event-create' }">Event Create</router-link>
    </nav>
  </div>
</template>

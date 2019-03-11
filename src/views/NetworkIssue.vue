<template>
  <div>
    <h1>Uh oh</h1>
    <h2>
      It looks like you are experiencing some network issues.
      Please click the back button and try again.
    </h2>
    <router-link :to="{ name: 'event-list' }">Or go back to the home page.</router-link>
  </div>
</template>

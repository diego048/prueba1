<template>
  <div>
    <form name="ask-question" method="POST" netlify netlify-honeypot="bot-field" onSubmit="submit">
      <input type="text" name="name" />
      <button type="submit">Submit</button>
    </form>
  </div>
</template>

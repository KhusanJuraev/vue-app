<template>
  <div>
    <div class="app-main-layout">
        <div class="app-page">
          <div>
            <div class="page-title">
              <h3>Профиль</h3>
            </div>

            <form class="form">
              <div class="input-field">
                <input
                    id="description"
                    type="text"
                >
                <label for="description">Имя</label>
                <span
                    class="helper-text invalid">name</span>
              </div>

              <button class="btn waves-effect waves-light" type="submit">
                Обновить
                <i class="material-icons right">send</i>
              </button>
            </form>
          </div>

        </div>

      <div class="fixed-action-btn">
        <a class="btn-floating btn-large blue" href="#">
          <i class="large material-icons">add</i>
        </a>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Profile"
}
</script>

<style scoped>

</style>
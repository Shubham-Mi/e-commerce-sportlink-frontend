<template>
  <div class="page-category">
    <div class="columns is-multiline">
      <div class="column is-12">
        <h2 class="is-size-2 has-text-centered">Trending of the Week</h2>
      </div>

      <div class="column is-3">
        <div class="box searchitems">
          <form action="/search" method="get">
            <input type="hidden" name="query" value="Cricket" />
            <button>
              <h3 class="is-size-4 searchname">Cricket</h3>
            </button>
          </form>
        </div>
      </div>
      <div class="column is-3">
        <div class="box searchitems">
          <form action="/search" method="get">
            <input type="hidden" name="query" value="Football" />
            <button>
              <h3 class="is-size-4 searchname">Football</h3>
            </button>
          </form>
        </div>
      </div>
      <div class="column is-3">
        <div class="box searchitems">
          <form action="/search" method="get">
            <input type="hidden" name="query" value="Kabaddi" />
            <button>
              <h3 class="is-size-4 searchname">Kabaddi</h3>
            </button>
          </form>
        </div>
      </div>
      <div class="column is-3">
        <div class="box searchitems">
          <form action="/search" method="get">
            <input type="hidden" name="query" value="Badminton" />
            <button>
              <h3 class="is-size-4 searchname">Badminton</h3>
            </button>
          </form>
        </div>
      </div>
      <div class="column is-3">
        <div class="box searchitems">
          <form action="/search" method="get">
            <input type="hidden" name="query" value="Hockey" />
            <button>
              <h3 class="is-size-4 searchname">Hockey</h3>
            </button>
          </form>
        </div>
      </div>
      <div class="column is-3">
        <div class="box searchitems">
          <form action="/search" method="get">
            <input type="hidden" name="query" value="Tennis" />
            <button>
              <h3 class="is-size-4 searchname">Tennis</h3>
            </button>
          </form>
        </div>
      </div>
      <div class="column is-3">
        <div class="box searchitems">
          <form action="/search" method="get">
            <input type="hidden" name="query" value="Wrestling" />
            <button>
              <h3 class="is-size-4 searchname">Wrestling</h3>
            </button>
          </form>
        </div>
      </div>
      <div class="column is-3">
        <div class="box searchitems">
          <form action="/search" method="get">
            <input type="hidden" name="query" value="Boxing" />
            <button>
              <h3 class="is-size-4 searchname">Boxing</h3>
            </button>
          </form>
        </div>
      </div>
      <div class="column is-3">
        <div class="box searchitems">
          <form action="/search" method="get">
            <input type="hidden" name="query" value="Motorsports" />
            <button>
              <h3 class="is-size-4 searchname">Motorsports</h3>
            </button>
          </form>
        </div>
      </div>
      <div class="column is-3">
        <div class="box searchitems">
          <form action="/search" method="get">
            <input type="hidden" name="query" value="Basketball" />
            <button>
              <h3 class="is-size-4 searchname">Basketball</h3>
            </button>
          </form>
        </div>
      </div>
    </div>
  </div>
</template>

<style>
.searchitems {
  padding: 0;
}

button {
  background: none;
  border: none;
  cursor: pointer;
  height: 100%;
  width: 100%;
}
</style>

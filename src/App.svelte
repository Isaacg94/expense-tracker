<script lang="ts">
  import "bulma/css/bulma.css";
</script>

<svelte:head>
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin=true />
  <link
    href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600;700&display=swap"
    rel="stylesheet"
  />
</svelte:head>

<div class="container p-3">
  <h1 class="is-size-1 has-text-weight-bold mt-6 mb-6">Expense Tracker</h1>
  <div class="columns is-3">
    <div class="column is-rounded has-background-white-ter">
      <div class="has-text-weight-semibold menu-label">Categories</div>
      <div>
        <ul class="menu-list">
          <li><a href={'#'}>Home</a></li>
          <li>
            <a href={'#'}>Work</a>
          </li>
          <li><a href={'#'} class="is-active">Social</a></li>
          <li><a href={'#'}>College</a></li>
        </ul>
      </div>
      <div class="mt-5 mb-5">
        <button class="button is-primary is-rounded"> Add New </button>
      </div>
    </div>
    <div class="column is-three-fifths">
      <div class="has-text-weight-semibold menu-label">Transactions</div>

      <div class="has-text-weight-semibold mb-5	">Social</div>

      <div class="tile is-ancestor">
        <div class="tile is-vertical ">
          <div class="tile">
            <div class="tile is-parent is-vertical">
              <article
                class="tile has-background-light is-child notification box"
              >
                <div class="has-text-weight-semibold has-text-info">
                  + New Transaction
                </div>
                <p
                  class="is-size-7 has-text-grey-light	 has-text-weight-semibold"
                >
                  Add New Expense
                </p>
              </article>
            </div>
          </div>
          <div class="tile">
            <div class="tile is-parent is-vertical">
              <article
                class="tile has-background-white is-child notification box"
              >
                <div class="has-text-weight-semibold">
                  Have drinks with Natasha
                </div>
                <p
                  class="is-size-7 has-text-grey-light	 has-text-weight-semibold"
                >
                  14 Feb 2022
                </p>
              </article>
            </div>
          </div>
          <div class="tile">
            <div class="tile is-parent is-vertical">
              <article
                class="tile has-background-white is-child notification box"
              >
                <div class="has-text-weight-semibold">
                  Go zip lining with Benny
                </div>
                <p
                  class="is-size-7 has-text-grey-light	 has-text-weight-semibold"
                >
                  22 Feb 2022
                </p>
              </article>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="column">
      <div class="has-text-weight-semibold menu-label">Profile</div>
      <div class="card">
        <div class="card-content has-text-centered">
          <div class="media">
            <div class="is-centered">
				<figure class="image is-256x256 m-3">
					<img class="is-rounded" src="https://bulma.io/images/placeholders/256x256.png" alt="s">
				  </figure>
            </div>
          </div>
          <div class="has-text-weight-semibold">Welcome Raymond!</div>
          <div
            class="is-size-6 mt-2 has-text-grey-light	 has-text-weight-semibold"
          >
            Profile
          </div>
          <div
            class="is-size-6 mt-2 has-text-grey-light	 has-text-weight-semibold"
          >
            Settings
          </div>
          <div
            class="is-size-6 mt-2 has-text-grey-light	 has-text-weight-semibold"
          >
            Logout
          </div>
        </div>
      </div>

	  <div class="box is-rounded">
		<div class="has-text-weight-semibold menu-label">Income</div>

		<div class="has-text-weight-semibold is-size-4	">$4,690</div>
	  </div>
      <div class="box is-rounded">
		<div class="has-text-weight-semibold menu-label">Expense</div>

		<div class="has-text-weight-semibold is-size-4	">$1,690</div>
	  </div>
    </div>
  </div>
</div>

<style>
  .container {
    font-family: "Poppins", sans-serif;
  }
</style>

<template>
  <div>
    <section class="bg-black grid grid-cols-1 xl:grid-cols-3">
      <div class="order-2 xl:order-1 xl:col-span-1 flex items-center">
        <div class="px-8 py-16 xl:p-8">
          <h1 class="text-white mb-6">
            Honoring the Officers of January 6<span class="lowercase">th</span>
          </h1>
          <p class="text-white text-xl mb-4">
            Congress passed a law requiring this plaque to be displayed at the U.S.
            Capitol to honor the officers who defended it on January 6, 2021. It has never
            been publicly mounted. The same administration whose allies incited that crowd
            now promotes a sanitized version of events.
          </p>
        </div>
      </div>
      <img
        src="/images/plaque.jpg"
        alt="January 6th Plaque"
        class="order-2 col-span-2 hidden xl:block w-full"
      />
      <img
        src="/images/plaque-mobile.jpg"
        alt="January 6th Plaque"
        class="order-1 xl:hidden w-full"
      />
    </section>

    <section class="container px-8 py-16 xl:p-24">
      <blockquote class="like-h1 mb-2">
        "This Jan. 6 plaque was made to honor law enforcement. It's nowhere to be found at
        the Capitol."
      </blockquote>
      <p class="text-sm blockquote-label">
        <a
          target="_blank"
          href="https://www.npr.org/2026/01/06/nx-s1-5668076/january-6-plaque-law-enforcement-capitol"
        >
          From NPR / AP Reporting
        </a>
      </p>
    </section>

    <section class="px-8 py-16 xl:p-8" id="key-links">
      <div class="grid grid-cols-1 lg:grid-cols-3 gap-8 mb-8">
        <article class="card bg-gray-100 rounded-xl p-6 pb-2">
          <h3 class="mb-6">Plaque Story</h3>
          <ul>
            <li class="mb-4">
              <a
                href="https://www.npr.org/2026/01/06/nx-s1-5668076/january-6-plaque-law-enforcement-capitol"
                target="_blank"
                rel="noopener"
              >
                Congress breaks the law: plaque missing from the Capitol
              </a>
            </li>

            <li class="mb-4">
              <a
                href="https://www.latimes.com/world-nation/story/2026-01-05/this-jan-6-plaque-was-made-to-honor-law-enforcement-its-nowhere-to-be-found"
                target="_blank"
                rel="noopener"
              >
                LA Times: The officers' plaque that never made it to the wall
              </a>
            </li>

            <li class="mb-4">
              <a
                href="https://www.policeforum.org/trending25jan25"
                target="_blank"
                rel="noopener"
              >
                Police leaders: remembering the officers who held the line
              </a>
            </li>
          </ul>
        </article>

        <article class="card bg-gray-100 rounded-xl p-6 pb-2">
          <h3 class="mb-6">What Jan. 6 Looked Like</h3>

          <ul>
            <li class="mb-4">
              <a
                href="https://apps.npr.org/jan-6-archive/"
                target="_blank"
                rel="noopener"
              >
                NPR visual archive of the Capitol attack
              </a>
            </li>

            <li class="mb-4">
              <a
                href="https://www.youtube.com/watch?v=8u5Sby-uuEw"
                target="_blank"
                rel="noopener"
              >
                How Jan. 6 evidence is being used in court and politics
              </a>
            </li>
          </ul>
        </article>

        <article class="card bg-gray-100 rounded-xl p-6 pb-2">
          <h3 class="mb-6">Deaths &amp; Injuries</h3>

          <ul>
            <li class="mb-4">
              <a
                href="https://www.nytimes.com/2022/01/05/us/politics/jan-6-capitol-deaths.html"
                target="_blank"
                rel="noopener"
              >
                The people who died in connection with the riot
              </a>
            </li>

            <li class="mb-4">
              <a
                href="https://www.nbcnews.com/politics/justice-department/doj-finds-officers-suicide-jan-6-was-death-line-duty-rcna100648"
                target="_blank"
                rel="noopener"
              >
                Officer suicide ruled a line-of-duty death
              </a>
            </li>
          </ul>
        </article>
      </div>

      <div class="grid grid-cols-1 lg:grid-cols-3 gap-8 mb-8">
        <article class="card bg-gray-100 rounded-xl p-6 pb-2">
          <h3 class="mb-6">By the Numbers</h3>

          <ul>
            <li class="mb-4">
              <a
                href="https://abcnews.go.com/US/jan-6-capitol-attack-investigation-stands-numbers-doj/story?id=117353000"
                target="_blank"
                rel="noopener"
              >
                DOJ/ABC: 1,600+ defendants and hundreds of assaults on officers
              </a>
            </li>

            <li class="mb-4">
              <a
                href="https://en.wikipedia.org/wiki/Criminal_proceedings_in_the_January_6_United_States_Capitol_attack"
                target="_blank"
                rel="noopener"
              >
                Criminal proceedings overview: every major charge category
              </a>
            </li>
          </ul>
        </article>

        <article class="card bg-gray-100 rounded-xl p-6 pb-2">
          <h3 class="mb-6">Sedition Cases</h3>

          <ul>
            <li class="mb-4">
              <a
                href="https://www.justice.gov/archives/opa/pr/jury-convicts-four-leaders-proud-boys-seditious-conspiracy-related-us-capitol-breach"
                target="_blank"
                rel="noopener"
              >
                Proud Boys leaders convicted of seditious conspiracy
              </a>
            </li>

            <li class="mb-4">
              <a
                href="https://www.justice.gov/archives/opa/pr/four-oath-keepers-found-guilty-seditious-conspiracy-related-us-capitol-breach"
                target="_blank"
                rel="noopener"
              >
                Oath Keepers leaders convicted of seditious conspiracy
              </a>
            </li>
          </ul>
        </article>
        <article class="card bg-gray-100 rounded-xl p-6 pb-2">
          <h3 class="mb-6">Assaults on Officers</h3>

          <ul>
            <li class="mb-4">
              <a
                href="https://www.lawfaremedia.org/article/the-high-water-mark-of-the-jan.-6-prosecutions"
                target="_blank"
                rel="noopener"
              >
                Lawfare: high-water mark of prosecutions and violent cases
              </a>
            </li>
          </ul>
        </article>
      </div>

      <div class="grid grid-cols-1 lg:grid-cols-3 gap-8 mb-8">
        <article class="card bg-gray-100 rounded-xl p-6 pb-2">
          <h3 class="mb-6">Mass Pardons</h3>

          <ul>
            <li class="mb-4">
              <a
                href="https://www.govinfo.gov/app/details/FR-2025-01-29/2025-01950"
                target="_blank"
                rel="noopener"
              >
                Proclamation 10887: full text of the January 6 pardons
              </a>
            </li>

            <li class="mb-4">
              <a
                href="https://www.npr.org/2025/01/20/g-s1-36809/trump-pardons-january-6-riot"
                target="_blank"
                rel="noopener"
              >
                NPR: 1,500 January 6 defendants walk free
              </a>
            </li>

            <li class="mb-4">
              <a
                href="https://www.npr.org/2025/01/30/nx-s1-5276336/donald-trump-jan-6-rape-assault-pardons-rioters"
                target="_blank"
                rel="noopener"
              >
                NPR: Many pardoned rioters already had serious criminal records
              </a>
            </li>
          </ul>
        </article>

        <article class="card bg-gray-100 rounded-xl p-6 pb-2">
          <h3 class="mb-6">New Crimes After Pardons</h3>

          <ul>
            <li class="mb-4">
              <a
                href="https://www.citizensforethics.org/reports-investigations/crew-reports/at-least-33-pardoned-insurrectionists-face-other-criminal-charges-but-many-are-now-going-free/"
                target="_blank"
                rel="noopener"
              >
                CREW: 33 pardoned insurrectionists facing other charges
              </a>
            </li>

            <li class="mb-4">
              <a
                href="https://www.citizensforethics.org/reports-investigations/crew-investigations/at-least-10-pardoned-insurrectionists-face-other-criminal-charges/"
                target="_blank"
                rel="noopener"
              >
                CREW: the worst reoffenders, from plots to new violence
              </a>
            </li>

            <li class="mb-4">
              <a
                href="https://19thnews.org/2026/01/january-6-pardons-arrests/"
                target="_blank"
                rel="noopener"
              >
                The 19th: dozens of pardoned rioters arrested again
              </a>
            </li>
          </ul>
        </article>

        <article class="card bg-gray-100 rounded-xl p-6 pb-2">
          <h3 class="mb-6">Rewriting the Story</h3>

          <ul>
            <li class="mb-4">
              <a
                href="https://www.democracydocket.com/news-alerts/trump-white-house-publishes-jan-6-website/"
                target="_blank"
                rel="noopener"
              >
                Democracy Docket: new Jan. 6 website rewrites the coup attempt
              </a>
            </li>

            <li class="mb-4">
              <a
                href="https://www.washingtonpost.com/politics/2026/01/06/january-6-anniversary-memorial-us-capitol/"
                target="_blank"
                rel="noopener"
              >
                Washington Post: a hidden plaque and the fight over memory
              </a>
            </li>
          </ul>
        </article>
      </div>
    </section>
  </div>
</template>

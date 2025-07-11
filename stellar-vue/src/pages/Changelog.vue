<template>
  <div className="flex flex-col min-h-screen overflow-hidden supports-[overflow:clip]:overflow-clip">

    <!-- Site header -->
    <Header />

    <!-- Page content -->
    <main class="grow">

      <!-- Content -->
      <section class="relative">

        <!-- Radial gradient -->
        <div class="absolute flex items-center justify-center top-0 -translate-y-1/2 left-1/2 -translate-x-1/2 pointer-events-none -z-10 w-[800px] aspect-square" aria-hidden="true">
          <div class="absolute inset-0 translate-z-0 bg-purple-500 rounded-full blur-[120px] opacity-30"></div>
          <div class="absolute w-64 h-64 translate-z-0 bg-purple-400 rounded-full blur-[80px] opacity-70"></div>
        </div>

        <!-- Particles animation -->
        <Particles class="absolute inset-0 h-96 -z-10" :quantity="15" />

        <!-- Illustration -->
        <div class="md:block absolute left-1/2 -translate-x-1/2 -mt-16 blur-2xl opacity-90 pointer-events-none -z-10" aria-hidden="true">
          <img src="../images/page-illustration.svg" class="max-w-none" width="1440" height="427" alt="Page Illustration">
        </div>

        <div class="max-w-6xl mx-auto px-4 sm:px-6">
          <div class="pt-32 pb-12 md:pt-40 md:pb-20">

            <!-- Page header -->
            <div class="text-center pb-12 md:pb-20">
              <h1 class="h1 bg-clip-text text-transparent bg-linear-to-r from-slate-200/60 via-slate-200 to-slate-200/60 pb-4">What's New</h1>
              <div class="max-w-3xl mx-auto">
                <p class="text-lg text-slate-400">New updates and improvements to Stellar.</p>
              </div>
            </div>

            <!-- Content -->
            <div class="max-w-3xl mx-auto">
              <div class="relative">
                <div class="absolute h-full top-4 left-[2px] w-0.5 bg-slate-800 [mask-image:linear-gradient(0deg,transparent,var(--color-white)_150px,var(--color-white))] -z-10 overflow-hidden after:absolute after:h-4 after:top-0 after:-translate-y-full after:left-0 after:w-0.5 after:bg-[linear-gradient(180deg,transparent,--theme(--color-purple-500/.65)_25%,--theme(--color-purple-200)_50%,--theme(--color-purple-500/.65)_75%,transparent)] after:animate-shine" aria-hidden="true"></div>
                <!-- Post -->
                <article class="pt-12 first-of-type:pt-0 group">
                  <div class="md:flex">
                    <div class="w-48 shrink-0">
                      <time class="text-sm inline-flex items-center bg-clip-text text-transparent bg-linear-to-r from-purple-500 to-purple-200 md:leading-8 before:w-1.5 before:h-1.5 before:rounded-full before:bg-purple-500 before:ring-4 before:ring-purple-500/30 mb-3">
                        <span class="ml-[1.625rem] md:ml-5">Nov 27, 2024</span>
                      </time>
                    </div>
                    <div class="grow ml-8 md:ml-0 pb-12 group-last-of-type:pb-0 border-b [border-image:linear-gradient(to_right,--theme(--color-slate-700/.3),--theme(--color-slate-700),--theme(--color-slate-700/.3))1] group-last-of-type:border-none">
                      <header>
                        <h2 class="text-2xl font-bold bg-clip-text text-transparent bg-linear-to-r from-slate-200/60 via-slate-200 to-slate-200/60 leading-8 pb-6">Weekly Update: Stellar X</h2>
                      </header>
                      <figure class="bg-linear-to-b from-slate-300/20 to-transparent rounded-3xl p-px mb-8">
                        <img class="w-full rounded-[inherit]" src="../images/changelog-01.png" width="574" height="326" alt="Changelog 01">
                      </figure>
                      <div class="prose max-w-none text-slate-400 prose-p:leading-relaxed prose-a:text-purple-500 prose-a:no-underline hover:prose-a:underline prose-strong:text-slate-50 prose-strong:font-medium">
                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
                        <p>Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur excepteur sint occaecat cupidatat non proident.</p>
                      </div>
                    </div>
                  </div>
                </article>
                <!-- Post -->
                <article class="pt-12 first-of-type:pt-0 group">
                  <div class="md:flex">
                    <div class="w-48 shrink-0">
                      <time class="text-sm inline-flex items-center bg-clip-text text-transparent bg-linear-to-r from-purple-500 to-purple-200 md:leading-8 before:w-1.5 before:h-1.5 before:rounded-full before:bg-purple-500 before:ring-4 before:ring-purple-500/30 mb-3">
                        <span class="ml-[1.625rem] md:ml-5">Nov 22, 2024</span>
                      </time>
                    </div>
                    <div class="grow ml-8 md:ml-0 pb-12 group-last-of-type:pb-0 border-b [border-image:linear-gradient(to_right,--theme(--color-slate-700/.3),--theme(--color-slate-700),--theme(--color-slate-700/.3))1] group-last-of-type:border-none">
                      <header>
                        <h2 class="text-2xl font-bold bg-clip-text text-transparent bg-linear-to-r from-slate-200/60 via-slate-200 to-slate-200/60 leading-8 pb-6">Refreshed main menu navigation</h2>
                      </header>
                      <figure class="bg-linear-to-b from-slate-300/20 to-transparent rounded-3xl p-px mb-8">
                        <img class="w-full rounded-[inherit]" src="../images/changelog-02.png" width="574" height="326" alt="Changelog 02">
                      </figure>
                      <div class="prose max-w-none text-slate-400 prose-p:leading-relaxed prose-a:text-purple-500 prose-a:no-underline hover:prose-a:underline prose-strong:text-slate-50 prose-strong:font-medium">
                        <p>Better align your teams and partners around standardized product principles and consistent implementation standards using the latest architecture shape pack.</p>
                        <ul>
                          <li>Streamline intake with workflows, templates, and automations</li>
                          <li>See realtime updates in Slack and get notified when your task is complete</li>
                          <li>Receive requests in Stellar in a shared team inbox</li>
                        </ul>
                        <p>Subscribe to get notified of key changes in the views you care about most. Opt-in to <a href="#0">receive a notification</a> when tasks are added to the view or when issues are completed or canceled.</p>
                      </div>
                    </div>
                  </div>
                </article>
                <!-- Post -->
                <article class="pt-12 first-of-type:pt-0 group">
                  <div class="md:flex">
                    <div class="w-48 shrink-0">
                      <time class="text-sm inline-flex items-center bg-clip-text text-transparent bg-linear-to-r from-purple-500 to-purple-200 md:leading-8 before:w-1.5 before:h-1.5 before:rounded-full before:bg-purple-500 before:ring-4 before:ring-purple-500/30 mb-3">
                        <span class="ml-[1.625rem] md:ml-5">Nov 4, 2024</span>
                      </time>
                    </div>
                    <div class="grow ml-8 md:ml-0 pb-12 group-last-of-type:pb-0 border-b [border-image:linear-gradient(to_right,--theme(--color-slate-700/.3),--theme(--color-slate-700),--theme(--color-slate-700/.3))1] group-last-of-type:border-none">
                      <header>
                        <h2 class="text-2xl font-bold bg-clip-text text-transparent bg-linear-to-r from-slate-200/60 via-slate-200 to-slate-200/60 leading-8 pb-6">New cloud architecture</h2>
                      </header>
                      <figure class="bg-linear-to-b from-slate-300/20 to-transparent rounded-3xl p-px mb-8">
                        <img class="w-full rounded-[inherit]" src="../images/changelog-03.png" width="574" height="326" alt="Changelog 03">
                      </figure>
                      <div class="prose max-w-none text-slate-400 prose-p:leading-relaxed prose-a:text-purple-500 prose-a:no-underline hover:prose-a:underline prose-strong:text-slate-50 prose-strong:font-medium">
                        <p>Newly created diagrams are now editable, full screen mode for more editing real estate, and both apps are updated to the latest version supporting new diagram types (eg. C4 architecture).</p>
                        <p>Create professional-looking diagrams with line jumps, making it easy to navigate complex diagrams with ease. You can also apply jumps to individual lines or the entire diagram.</p>
                      </div>
                    </div>
                  </div>
                </article>
                <!-- Post -->
                <article class="pt-12 first-of-type:pt-0 group">
                  <div class="md:flex">
                    <div class="w-48 shrink-0">
                      <time class="text-sm inline-flex items-center bg-clip-text text-transparent bg-linear-to-r from-purple-500 to-purple-200 md:leading-8 before:w-1.5 before:h-1.5 before:rounded-full before:bg-purple-500 before:ring-4 before:ring-purple-500/30 mb-3">
                        <span class="ml-[1.625rem] md:ml-5">Oct 31, 2024</span>
                      </time>
                    </div>
                    <div class="grow ml-8 md:ml-0 pb-12 group-last-of-type:pb-0 border-b [border-image:linear-gradient(to_right,--theme(--color-slate-700/.3),--theme(--color-slate-700),--theme(--color-slate-700/.3))1] group-last-of-type:border-none">
                      <header>
                        <h2 class="text-2xl font-bold bg-clip-text text-transparent bg-linear-to-r from-slate-200/60 via-slate-200 to-slate-200/60 leading-8 pb-6">Updates to the Filtering API</h2>
                      </header>
                      <figure class="bg-linear-to-b from-slate-300/20 to-transparent rounded-3xl p-px mb-8">
                        <img class="w-full rounded-[inherit]" src="../images/changelog-04.png" width="574" height="326" alt="Changelog 04">
                      </figure>
                      <div class="prose max-w-none text-slate-400 prose-p:leading-relaxed prose-a:text-purple-500 prose-a:no-underline hover:prose-a:underline prose-strong:text-slate-50 prose-strong:font-medium">
                        <p>We understand that who you've worked with in the past is often who you'll work with in the future, and are now placing a higher emphasis on making your past mentions more accessible. This means your previous collaborators will be front and center, ready for future collaboration.</p>
                      </div>
                    </div>
                  </div>
                </article>
              </div>
            </div>

            <!-- Pagination -->
            <div class="max-w-3xl mx-auto">
              <ul class="flex items-center justify-between mt-12 pl-8 md:pl-48">
                <li>
                  <span class="btn-sm text-slate-700 transition duration-150 ease-in-out group [background:linear-gradient(var(--color-slate-900),var(--color-slate-900))_padding-box,conic-gradient(var(--color-slate-400),var(--color-slate-700)_25%,var(--color-slate-700)_75%,var(--color-slate-400)_100%)_border-box] relative before:absolute before:inset-0 before:bg-slate-800/30 before:rounded-full before:pointer-events-none cursor-not-allowed">
                    <span class="relative inline-flex items-center">
                      <span class="tracking-normal text-slate-700 mr-1">&lt;-</span> Previous Page
                    </span>
                  </span>
                </li>
                <li>
                  <a class="btn-sm text-slate-300 hover:text-white transition duration-150 ease-in-out group [background:linear-gradient(var(--color-slate-900),var(--color-slate-900))_padding-box,conic-gradient(var(--color-slate-400),var(--color-slate-700)_25%,var(--color-slate-700)_75%,var(--color-slate-400)_100%)_border-box] relative before:absolute before:inset-0 before:bg-slate-800/30 before:rounded-full before:pointer-events-none" href="#0">
                    <span class="relative inline-flex items-center">
                      Next Page <span class="tracking-normal text-purple-500 group-hover:translate-x-0.5 transition-transform duration-150 ease-in-out ml-1">-&gt;</span>
                    </span>
                  </a>
                </li>
              </ul>
            </div>

          </div>
        </div>

      </section>

      <Cta />

    </main>

    <!-- Site footer -->
    <Footer />

  </div>
</template>

<script>
import Header from '../partials/Header.vue'
import Particles from '../partials/Particles.vue'
import Cta from '../partials/Cta03.vue'
import Footer from '../partials/Footer.vue'

export default {
  name: 'Changelog',
  components: {
    Header,
    Particles,
    Cta,
    Footer,
  },
}
</script>
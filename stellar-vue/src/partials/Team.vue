<template>
  <section class="relative">
    <!-- Radial gradient -->
    <div class="absolute inset-0 overflow-hidden pointer-events-none -z-10" aria-hidden="true">
      <div class="absolute flex items-center justify-center top-0 -translate-y-1/2 left-1/2 -translate-x-1/2 w-1/3 aspect-square">
        <div class="absolute inset-0 translate-z-0 bg-purple-500 rounded-full blur-[120px] opacity-50"></div>
      </div>
    </div>
    <div class="max-w-6xl mx-auto px-4 sm:px-6">
      <div class="py-12 md:py-20">
        <!-- Content -->
        <div class="max-w-3xl mx-auto text-center pb-12 md:pb-20">
          <h2 class="h2 bg-clip-text text-transparent bg-linear-to-r from-slate-200/60 via-slate-200 to-slate-200/60 pb-4">We are a happy, small team</h2>
          <p class="text-lg text-slate-400">Various versions of Lorem Ipsum have evolved over the years, sometimes by accident, sometimes on purpose, and by injecting humour and the like.</p>
        </div>
        <!-- Team members -->
        <div class="grid sm:grid-cols-2 lg:grid-cols-3 xl:grid-cols-4 gap-2 sm:gap-6">
          <template v-for="item in items">
            <div class="relative flex items-center justify-between py-4 pl-4 pr-3 group before:absolute before:inset-0 before:-z-10 before:border before:border-slate-300 before:bg-slate-700 before:opacity-0 hover:before:opacity-10 transition-opacity focus-within:before:opacity-10 before:rounded-xl before:transition-opacity">
              <div class="flex items-center space-x-4">
                <img class="shrink-0" :src="item.img" width="48" height="48" :alt="item.name" />
                <div class="grow">
                  <div class="font-bold text-slate-100 mb-0.5">{{ item.name }}</div>
                  <div class="text-sm text-purple-500 font-medium">{{ item.role }}</div>
                </div>
              </div>
              <a class="shrink-0 text-slate-500 md:opacity-0 group-hover:opacity-100 focus-within:opacity-100 focus:outline-hidden group-hover:before:absolute group-hover:before:inset-0" :href="item.twitter" :aria-label="`${item.name}'s Twitter`">
                <svg class="fill-current" xmlns="http://www.w3.org/2000/svg" width="24" height="24">
                  <path d="M11.297 13.807 7.424 18H5.276l5.019-5.436L5 6h4.43l3.06 3.836L16.025 6h2.147l-4.688 5.084L19 18h-4.32l-3.383-4.193Zm3.975 2.975h1.19L8.783 7.155H7.507l7.766 9.627Z" />
                </svg>
              </a>
            </div>
          </template>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
import Member01 from '../images/team-01.png'
import Member02 from '../images/team-02.png'
import Member03 from '../images/team-03.png'
import Member04 from '../images/team-04.png'
import Member05 from '../images/team-05.png'
import Member06 from '../images/team-06.png'
import Member07 from '../images/team-07.png'
import Member08 from '../images/team-08.png'
import Member09 from '../images/team-09.png'
import Member10 from '../images/team-10.png'
import Member11 from '../images/team-11.png'
import Member12 from '../images/team-12.png'
import Member13 from '../images/team-13.png'
import Member14 from '../images/team-14.png'
import Member15 from '../images/team-15.png'
import Member16 from '../images/team-16.png'
import Member17 from '../images/team-17.png'
import Member18 from '../images/team-18.png'
import Member19 from '../images/team-19.png'
import Member20 from '../images/team-20.png'

export default {
  name: 'Team',
  setup() {
    const items = [
      {
        img: Member01,
        name: 'Sarah Barnekow',
        role: 'CEO & Co-founder',
        twitter: '#0',
      },
      {
        img: Member02,
        name: 'Alex Suevalov',
        role: 'Tech Lead',
        twitter: '#0',
      },
      {
        img: Member03,
        name: 'Mark Lamprecht',
        role: 'Software Engineer',
        twitter: '#0',
      },
      {
        img: Member04,
        name: 'Scott Bailey',
        role: 'Software Engineer',
        twitter: '#0',
      },
      {
        img: Member05,
        name: 'Vedant Hegde',
        role: 'Customer Experience',
        twitter: '#0',
      },
      {
        img: Member06,
        name: 'Lucy Radux',
        role: 'Marketing Manager',
        twitter: '#0',
      },
      {
        img: Member07,
        name: 'Devani Janssen',
        role: 'Product Design',
        twitter: '#0',
      },
      {
        img: Member08,
        name: 'Dima Trystram',
        role: 'Customer Success',
        twitter: '#0',
      },
      {
        img: Member09,
        name: 'Fraser Davidson',
        role: 'Customer Success',
        twitter: '#0',
      },
      {
        img: Member10,
        name: 'William Adkins',
        role: 'Customer Experience',
        twitter: '#0',
      },
      {
        img: Member11,
        name: 'Debbie Poulin',
        role: 'Head of Talent',
        twitter: '#0',
      },
      {
        img: Member12,
        name: 'James Kudinov',
        role: 'Product Design',
        twitter: '#0',
      },
      {
        img: Member13,
        name: 'Zhenya Rynzhuk',
        role: 'Software Engineer',
        twitter: '#0',
      },
      {
        img: Member14,
        name: 'Mary Maka',
        role: 'Enterprise Architect',
        twitter: '#0',
      },
      {
        img: Member15,
        name: 'Monty Hayton',
        role: 'Video Producer',
        twitter: '#0',
      },
      {
        img: Member16,
        name: 'Srdjan Vidakovic',
        role: 'Operations Manager',
        twitter: '#0',
      },
      {
        img: Member17,
        name: 'David Cran',
        role: 'Financial Analyst',
        twitter: '#0',
      },
      {
        img: Member18,
        name: 'Jacek Janiczak',
        role: 'Data Engineer',
        twitter: '#0',
      },
      {
        img: Member19,
        name: 'Tommy Chandra',
        role: 'Head of Design',
        twitter: '#0',
      },
      {
        img: Member20,
        name: 'Ally Golovko',
        role: 'Software Engineer',
        twitter: '#0',
      },
    ]

    return {
      items
    }
  }
}
</script>
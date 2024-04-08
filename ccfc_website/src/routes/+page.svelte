<script lang="ts">
  import IconGithub from '$lib/components/icons/IconGithub.svelte'
  import IconTelegram from '$lib/components/icons/IconTelegram.svelte'
  import IconX from '$lib/components/icons/IconX.svelte'
  import { PROJECT_URL } from '$lib/constants'
  import { ConicGradient } from '@skeletonlabs/skeleton'
  import Saos from 'saos'
  import IconCcfc from '$lib/components/icons/IconCCFC.svelte'
  import VideoEmbed from '$lib/components/core/VideoEmbed.svelte'
  import IconWhitepaper from '$lib/components/icons/IconWhitepaper.svelte'
</script>

<div
  class="mb-12 mt-12 flex flex-col flex-nowrap content-center items-center px-4 lg:mt-24"
>
  <div class="flex flex-col items-center">
    <Saos
      animation={'scale-down-center 0.6s cubic-bezier(0.250, 0.460, 0.450, 0.940) both'}
    >
      <div
        class="size-24 rounded-full transition duration-700 ease-in-out *:size-24 hover:scale-150 hover:shadow-lg"
      >
        <IconCcfc />
      </div>
    </Saos>
    <img class="mt-12" src="/_assets/ccfc-dao.svg" alt="CCFC brand" />
  </div>
  <div
    class="mt-10 flex max-w-4xl flex-row items-center gap-6 max-sm:flex-col *:max-sm:w-60"
  >
    <a
      type="button"
      title="Participate in SNS sale"
      class="variant-filled btn token-sale"
      href="https://nns.ic0.app/launchpad/"
      target="_blank"
    >
      <span class="text-left">SNS token sale will start soon!</span>
    </a>
  </div>
  <div class="mt-6 max-w-screen-sm">
    <p class="text-center text-lg font-normal antialiased">
      <a
        class="text-ccfc font-bold underline underline-offset-4"
        href={PROJECT_URL}
        target="_blank">Cerveza Cristal Fan Coin</a
      >
      (CCFC) is an absolute meme coin embrazing the still nacent
      <a
        class="text-secondary-500 font-bold underline underline-offset-4"
        href="https://internetcomputer.org/"
        target="_blank"
      >
        Internet Computer
      </a>
      ecosystem. The meme coin is governed by a Decentralised Autonomous Organisaton
      (DAO), also known as Service Nervous System (SNS) on ICP. The concept of this
      DAO is
      <i>community first</i>, that's why the majority of the tokens are in the
      hands of the community.
    </p>
  </div>

  <div
    class="mt-10 flex max-w-4xl flex-row items-center gap-6 max-sm:flex-col *:max-sm:w-60"
  >
    <a
      type="button"
      title="Follow on Twitter"
      class="variant-filled btn bg-slate-950"
      href="https://twitter.com/cc_fan_coin"
      target="_blank"
    >
      <span><IconX /></span>
      <span class="text-left">Twitter</span>
    </a>
    <a
      type="button"
      title="Join the Community"
      class="variant-filled btn bg-slate-950"
      href="https://t.me/+9RXL44rH8m00YmY0"
      target="_blank"
    >
      <span><IconTelegram /></span>
      <span class="text-left">Community</span>
    </a>
    <a
      type="button"
      title="View Source Code"
      class="variant-filled btn bg-slate-950"
      href="https://github.com/CCFC-labs/ccfc-sns"
      target="_blank"
    >
      <span class="*:scale-125"><IconGithub /></span>
      <span class="text-left">Source Code</span>
    </a>
    <a
      type="button"
      title="Read the whitepaper"
      class="variant-filled btn bg-slate-950"
      href="https://github.com/CCFC-labs/ccfc-sns/blob/main/whitepaper/en.md"
      target="_blank"
    >
      <span class="*:scale-125"><IconWhitepaper /></span>
      <span class="text-left">Whitepaper</span>
    </a>
    <!-- <a
      type="button"
      title="Exchange Tokens"
      class="variant-filled btn bg-slate-950"
      href=""
      target="_blank"
    >
      <span><IconExchangeDollar /></span>
      <span class="text-left">Exchange</span>
    </a> -->
  </div>

  <div
    class="mt-12 flex w-full max-w-screen-sm flex-col flex-nowrap content-center items-center text-lg sm:mt-24"
  >
    <h2 id="mission" class="h2 mb-10 font-extrabold uppercase">Our mission</h2>
    Not only are we beer lovers but also huge fans of Star Wars. So facing what Cerveza
    Cristal managed - merging our two passions - we saw that it deserves a bigger
    place in the meme world.
    <Saos
      once={true}
      animation={'slide-top 0.6s cubic-bezier(.25,.46,.45,.94) both'}
    >
      <VideoEmbed />
    </Saos>
    <p>
      Learn more about the origins of this meme on
      <a
        class="text-secondary-500 font-bold underline underline-offset-4"
        href="https://en.wikipedia.org/wiki/The_Force_is_with_Cristal_Beer"
        target="_blank"
      >
        its wiki page
      </a>.
    </p>
  </div>

  <div
    class="mt-12 flex w-full max-w-4xl flex-col flex-nowrap content-center items-center sm:mt-24"
  >
    <h2 id="tokenomics" class="h2 font-extrabold uppercase">Tokenomics</h2>
    <div class="mt-8 flex w-full flex-col justify-evenly gap-y-4 sm:flex-row">
      <Saos
        once={true}
        animation={'slide-top 0.6s cubic-bezier(.25,.46,.45,.94) both'}
      >
        <div class="flex flex-col gap-4 text-center">
          <h3 class="h3 font-bold">
            <p>Token Name</p>
            <p class="text-ccfc"
              >Cerveza Cristal Fan Coin
              <!-- <a
                class="underline underline-offset-4"
                title="CCFC Token Info"
                href="/#"
                target="_blank">Cerveza Cristal Fan Coin</a
              > -->
            </p>
          </h3>
          <h3 class="h3 font-bold">
            <p>Token Symbol</p>
            <p class="text-ccfc"
              >CCFC
              <!-- <a
                class="underline underline-offset-4"
                title="Buy CCFC Tokens"
                href="/#"
                target="_blank"></a
              > -->
            </p>
          </h3>
          <h3 class="h3 font-bold">
            <p>Total Supply</p>
            <p class="text-ccfc">1,000,000,000</p>
          </h3>
        </div>
      </Saos>
      <Saos
        once={true}
        animation={'slide-top 0.6s cubic-bezier(.25,.46,.45,.94) both'}
      >
        <ConicGradient
          legend
          width="w-36"
          regionCone="hover:scale-125 hover:shadow-lg hover:-rotate-12 transition duration-700 ease-in-out"
          stops={[
            {
              label: 'Dev Team',
              color: '#4F46E5',
              start: 0,
              end: 10
            },
            {
              label: 'SNS Swap',
              color: '#0FBA81',
              start: 10,
              end: 50
            },
            {
              label: 'DAO Treasury - Community & Marketing',
              color: 'rgba(234,179,8,0.7)',
              start: 50,
              end: 60
            },
            {
              label: 'DAO Treasury - DEX Liquidity',
              color: 'rgba(234,179,8,0.4)',
              start: 60,
              end: 100
            }
          ]}
        >
          <h3 class="h3 font-bold">Token Distribution</h3>
        </ConicGradient>
      </Saos>
    </div>
    <Saos
      once={true}
      animation={'slide-top 0.6s cubic-bezier(.25,.46,.45,.94) both'}
    >
      <div class="mt-4 max-w-screen-sm text-lg font-normal antialiased">
        <p
          >We are giving a majority share of the tokens to the community as this
          project shall be a community driven project. We want to ensure that
          enough liquidity is provided to exchanges and the project can further
          grow organically. We are not asking for any funds from the Neuron Fund
          as we believe this is not suitable for a meme coin project.
        </p>
      </div>
    </Saos>
    <Saos
      once={true}
      animation={'slide-top 0.6s cubic-bezier(.25,.46,.45,.94) both'}
    >
      <div class="mt-12 gap-4">
        <h3 class="h3 text-center font-bold">
          <p>Treasury usage</p>
        </h3>
        <div class="mt-4 max-w-screen-sm text-lg font-normal antialiased">
          <p>
            All of the ICP raised in the SNS token sale will belong to the DAO
            and are not used for any team funding. The team is working entirely
            out of their own pocket and are incentivised through the <span
              class="text-ccfc font-bold">CCFC</span
            >
            token itself. <span class="text-ccfc font-bold">80%</span>
            of the raised funds will be used to provide liquity as this is a crucial
            element for the success of any meme coin.
            <span class="text-ccfc font-bold">20%</span> will be used to incentivise
            marketing activity within the community. The DAO will be able to vote
            about those in detail.
          </p><br /><p class="font-bold">
            If more than 20k ICP are raised, we shall invest the surplus into
            building tools that foster the ICP Meme Coin ecosystem.
          </p><br />
          <p
            >Find full details about the sns launch in the <a
              class="text-secondary-500 font-bold underline underline-offset-4"
              href="https://github.com/CCFC-labs/ccfc-sns/blob/main/sns_init.yaml"
              target="_blank">SNS init file</a
            >.</p
          >
        </div>
      </div>
    </Saos>
  </div>
</div>

<style>
  /**
  * ----------------------------------------
  * animation slide-top http://animista.net
  * ----------------------------------------
  */
  @keyframes -global-slide-top {
    0% {
      transform: translateY(100px);
      opacity: 0;
    }
    100% {
      transform: translateY(0);
      opacity: 1;
    }
  }

  @keyframes -global-scale-down-center {
    0% {
      transform: scale(1.5);
    }
    100% {
      transform: scale(1);
    }
  }
</style>

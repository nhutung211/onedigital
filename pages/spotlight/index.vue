<template>
  <div>
    <HeroImage
      :src="require('~/assets/images/illustrations/Spotlight-banner.png')"
      alt="Spotlight Posts"
    />
    <main class="max-w-screen-xl px-4 mx-auto sm:px-6 lg:px-8">
      <Breadcrumbs />
      <section class="index-section">
        <article
          class="flex flex-col p-6 overflow-hidden bg-white rounded-lg shadow-lg xl:w-2/3 lg:w-2/3 sm:w-full mx-auto"
        >
          <h2 class="mb-2 text-lg font-bold">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              fill="none"
              viewBox="0 0 24 24"
              stroke="currentColor"
              class="inline-block mr-1 stroke-current stroke-2 icon-size text-blue"
            >
              <path
                strokeLinecap="round"
                strokeLinejoin="round"
                strokeWidth="{2}"
                d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z"
              />
            </svg>
            What We're Looking For
          </h2>

          <p class="mb-2">
            Our goal is simple: we want to see what you're doing with Vonage’s
            products, and we want you to share your story with the community.
          </p>
          <p class="mb-2">
            We're interested in technical tutorials on something original you
            have built, an innovative use case, or some interesting third-party
            integrations that use Vonage products.
          </p>
          <p class="mb-1">Successful submissions will be:</p>
          <p class="mb-2">
            <strong>Original.</strong> Literally, we want original work (nothing
            that has been published elsewhere). And more figuratively, we want
            to see original thought and interesting points of view we can't find
            anywhere else.
          </p>
          <p class="mb-2">
            <strong>Well-written.</strong> Before we can publish a post, it must
            conform to our
            <a
              class="text-purple-dark"
              href="https://learn.vonage.com/contributing/#writing-style-guide"
              >style guide</a
            >. We’re happy to help fine-tune, but submissions should be
            proofread and need only minor editing.
          </p>
          <p class="mb-2">
            <strong>Code-driven. </strong> The result of your post should be
            something a reader can build upon. The code should be clearly
            explained and helpfully split up.
          </p>
          <p class="mb-2">
            To get a better understanding of the sort of articles that we are
            looking for, please take a look at the ones that have been
            <a
              href="https://learn.vonage.com/blog/spotlight/"
              class="text-purple-dark"
              >successfully published</a
            >
          </p>

          <h2 class="mt-4 mb-2 text-lg font-bold">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              fill="none"
              viewBox="0 0 24 24"
              stroke="currentColor"
              class="inline-block mr-1 stroke-current stroke-2 icon-size text-blue"
            >
              <path
                strokeLinecap="round"
                strokeLinejoin="round"
                strokeWidth="{2}"
                d="M10 20l4-16m4 4l4 4-4 4M6 16l-4-4 4-4"
              />
            </svg>
            Does my post have to be about Vonage products?
          </h2>
          <p class="mb-2">
            Your posts must involve Vonage products. It can be any of them: SMS,
            Voice, Video, Verify, Conversation APIs, or one of the other tools
            of our communication suite.
          </p>

          <h2 class="mt-4 mb-2 text-lg font-bold">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              fill="none"
              viewBox="0 0 24 24"
              stroke="currentColor"
              class="inline-block mr-1 stroke-current stroke-2 icon-size text-blue"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                d="M20.618 5.984A11.955 11.955 0 0112 2.944a11.955 11.955 0 01-8.618 3.04A12.02 12.02 0 003 9c0 5.591 3.824 10.29 9 11.622 5.176-1.332 9-6.03 9-11.622 0-1.042-.133-2.052-.382-3.016zM12 9v2m0 4h.01"
              />
            </svg>

            What We're Not Looking For
          </h2>

          <ul class="pl-6 mb-2 list-disc">
            <li>Beginner-level tutorials on how to use Vonage APIs</li>
            <li>Thought leadership articles</li>
            <li>
              Introduction to third-party frameworks, programming languages, and
              modern development techniques
            </li>
            <li>Anything that is not a step-by-step tutorial</li>
            <li>
              Articles that have already been published on other platforms
            </li>
            <li>
              Tutorials on topics that we have already covered. You can check
              what we have already published on our
              <a class="text-purple-dark" href="https://learn.vonage.com/"
                >learning platform
              </a>
            </li>
          </ul>

          <h2 class="mb-2 text-lg font-bold">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              fill="none"
              viewBox="0 0 24 24"
              stroke="currentColor"
              class="inline-block mr-1 stroke-current stroke-2 icon-size text-blue"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="{2}"
                d="M16 7a4 4 0 11-8 0 4 4 0 018 0zM12 14a7 7 0 00-7 7h14a7 7 0 00-7-7z"
              />
            </svg>
            What's in it for You?
          </h2>
          <p class="mb-2">
            We pay $500 USD per post. Your tutorial will be published on our
            <a class="text-purple-dark" href="https://learn.vonage.com/"
              >learning platform</a
            >
            and may be shared in our newsletter or showcased during one of our
            streams.
          </p>
          <p class="mb-2">
            We make every effort to amplify the reach of each and every blog
            post on our site, and yours will be no exception; you'll have the
            Vonage marketing and social media teams behind you getting the word
            out about your work. Your success is our success.
          </p>
          <p class="mb-2">
            You can also choose to donate the $500 to a charity, making a
            difference in the technology industry.
          </p>

          <p class="mb-2">
            And Now Introducing:
            <a
              class="text-purple"
              href="https://www.nexmo.com/legacy-blog/2019/09/04/vonage-launches-spotlight-for-donations-program-dr"
              >Spotlight for Donations</a
            >
          </p>
          <p class="mb-2">
            Authors can now choose to pay it forward and donate their $500 to a
            charity making a difference in the technology industry.
          </p>

          <h2 class="mt-4 mb-2 text-lg font-bold">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              fill="none"
              viewBox="0 0 24 24"
              stroke="currentColor"
              class="inline-block mr-1 stroke-current stroke-2 icon-size text-blue"
            >
              <path
                strokeLinecap="round"
                strokeLinejoin="round"
                strokeWidth="{2}"
                d="M10.325 4.317c.426-1.756 2.924-1.756 3.35 0a1.724 1.724 0 002.573 1.066c1.543-.94 3.31.826 2.37 2.37a1.724 1.724 0 001.065 2.572c1.756.426 1.756 2.924 0 3.35a1.724 1.724 0 00-1.066 2.573c.94 1.543-.826 3.31-2.37 2.37a1.724 1.724 0 00-2.572 1.065c-.426 1.756-2.924 1.756-3.35 0a1.724 1.724 0 00-2.573-1.066c-1.543.94-3.31-.826-2.37-2.37a1.724 1.724 0 00-1.065-2.572c-1.756-.426-1.756-2.924 0-3.35a1.724 1.724 0 001.066-2.573c-.94-1.543.826-3.31 2.37-2.37.996.608 2.296.07 2.572-1.065z"
              />
              <path
                strokeLinecap="round"
                strokeLinejoin="round"
                strokeWidth="{2}"
                d="M15 12a3 3 0 11-6 0 3 3 0 016 0z"
              />
            </svg>
            How to Submit Your Article
          </h2>
          <p class="mb-2">
            You will need to submit a rough draft of your article in Markdown.
            The draft should be around 2000 words and include all the text, code
            examples, and images a reader would need to follow along with the
            tutorial.
          </p>

          <h2 class="mt-4 mb-2 text-lg font-bold">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              fill="none"
              viewBox="0 0 24 24"
              stroke="currentColor"
              class="inline-block mr-1 stroke-current stroke-2 icon-size text-blue"
            >
              <path
                strokeLinecap="round"
                strokeLinejoin="round"
                strokeWidth="{2}"
                d="M10.325 4.317c.426-1.756 2.924-1.756 3.35 0a1.724 1.724 0 002.573 1.066c1.543-.94 3.31.826 2.37 2.37a1.724 1.724 0 001.065 2.572c1.756.426 1.756 2.924 0 3.35a1.724 1.724 0 00-1.066 2.573c.94 1.543-.826 3.31-2.37 2.37a1.724 1.724 0 00-2.572 1.065c-.426 1.756-2.924 1.756-3.35 0a1.724 1.724 0 00-2.573-1.066c-1.543.94-3.31-.826-2.37-2.37a1.724 1.724 0 00-1.065-2.572c-1.756-.426-1.756-2.924 0-3.35a1.724 1.724 0 001.066-2.573c-.94-1.543.826-3.31 2.37-2.37.996.608 2.296.07 2.572-1.065z"
              />
              <path
                strokeLinecap="round"
                strokeLinejoin="round"
                strokeWidth="{2}"
                d="M15 12a3 3 0 11-6 0 3 3 0 016 0z"
              />
            </svg>
            The Process
          </h2>
          <p class="mb-2">
            When you send your draft via the submission form, our Developer
            Education Team will evaluate it to see if it's a good fit for the
            Vonage learning platform.
          </p>
          <p class="mb-2">
            At the end of the month, we will get back to you with feedback on
            whether the application was successful or not.
          </p>
          <p class="mb-2">
            If we think your article is in line with our needs and meets the
            quality standard, we will confirm we have accepted it.
          </p>
          <p class="mb-2">
            From the day of acceptance, we usually expect to have a final draft
            within 3 weeks. When the final draft is almost ready to go live, we
            will confirm a publication date.
          </p>
          <p class="mb-2">
            You will receive your payment the day that the article is published.
          </p>
          <p class="mb-2">
            Please note that submission is not a guarantee that your work will
            be published; we reserve the right to decline submissions that
            aren't right for our learning platform. We may also be unable to
            publish your work if we are unable to get a final draft within three
            weeks, so please set aside a few hours for revisions!
          </p>

          <h2 class="mt-4 mb-2 text-lg font-bold">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              fill="none"
              viewBox="0 0 24 24"
              stroke="currentColor"
              class="inline-block mr-1 stroke-current stroke-2 icon-size text-blue"
            >
              <path
                strokeLinecap="round"
                strokeLinejoin="round"
                strokeWidth="{2}"
                d="M7 16V4m0 0L3 8m4-4l4 4m6 0v12m0 0l4-4m-4 4l-4-4"
              />
            </svg>
            Who Owns Your Work?
          </h2>
          <p class="mb-2">
            You do! You grant Vonage an unlimited license to publish and promote
            your post, but you retain full ownership.
          </p>
          <p class="mb-2">
            This means you are free to re-publish elsewhere (on your own Medium
            page, for example). All we require is that you add a
            <code>rel=canonical</code> tag to your post wherever possible,
            naming the original post at Vonage the canonical URL.
          </p>

          <h2 class="mt-4 text-lg font-bold">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              fill="none"
              viewBox="0 0 24 24"
              stroke="currentColor"
              class="inline-block mr-1 stroke-current stroke-2 icon-size text-blue"
            >
              <path
                strokeLinecap="round"
                strokeLinejoin="round"
                strokeWidth="{2}"
                d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"
              />
            </svg>
            Submit Your Idea
          </h2>
          <form
            class="space-y-6"
            name="spotlight"
            method="POST"
            data-netlify="true"
            netlify-honeypot="some-info"
            action="/spotlight/success/"
          >
            <div class="hidden">
              <input type="hidden" name="form-name" value="spotlight" />
              <label
                >Don’t fill this out if you are human: <input name="some-info"
              /></label>
            </div>
            <div>
              <label for="name" class="block text-sm font-medium text-gray-700">
                Your Name
              </label>
              <div class="mt-1">
                <input
                  id="name"
                  name="name"
                  type="name"
                  autocomplete="name"
                  required
                  class="block w-full px-3 py-2 placeholder-gray-400 border border-gray-300 rounded-md shadow-sm appearance-none focus:outline-none focus:ring-indigo-500 focus:border-purple sm:text-sm"
                />
              </div>
            </div>
            <div>
              <label
                for="email_address"
                class="block text-sm font-medium text-gray-700"
              >
                Email Address
              </label>
              <div class="mt-1">
                <input
                  id="email_address"
                  name="email_address"
                  type="email_address"
                  autocomplete="email_address"
                  required
                  class="block w-full px-3 py-2 placeholder-gray-400 border border-gray-300 rounded-md shadow-sm appearance-none focus:outline-none focus:ring-indigo-500 focus:border-purple sm:text-sm"
                />
              </div>
            </div>
            <div>
              <label
                for="background"
                class="block text-sm font-medium text-gray-700"
              >
                Please write a few lines about your background for your author
                bio
              </label>
              <div class="mt-1">
                <textarea
                  id="background"
                  name="background"
                  rows="3"
                  class="block w-full px-3 py-2 placeholder-gray-400 border border-gray-300 rounded-md shadow-sm appearance-none focus:outline-none focus:ring-indigo-500 focus:border-purple sm:text-sm"
                  required
                ></textarea>
              </div>
            </div>
            <div>
              <label
                for="outline"
                class="block text-sm font-medium text-gray-700"
              >
                Paste in your draft
              </label>
              <div class="mt-1">
                <textarea
                  id="outline"
                  name="outline"
                  rows="10"
                  required
                  class="block w-full px-3 py-2 placeholder-gray-400 border border-gray-300 rounded-md shadow-sm appearance-none focus:outline-none focus:ring-indigo-500 focus:border-purple sm:text-sm"
                ></textarea>
              </div>
            </div>
            <div>
              <label
                for="product"
                class="block text-sm font-medium text-gray-700"
              >
                Which Vonage product are you using in your tutorial?
              </label>
              <div class="mt-1">
                <select
                  id="product"
                  name="product"
                  class="block w-full py-2 pl-3 border border-gray-300 rounded-md focus:outline-none focus:ring-indigo-500 focus:border-purple sm:text-sm"
                  required
                >
                  <option></option>
                  <option>SMS API</option>
                  <option>Account API</option>
                  <option>Alerts API - Subscription</option>
                  <option>Alerts API - Sending</option>
                  <option>Application API</option>
                  <option>Audit API</option>
                  <option>Conversation API</option>
                  <option>Dispatch API</option>
                  <option>External Accounts API</option>
                  <option>Media API</option>
                  <option>Messages API</option>
                  <option>Number Insight API</option>
                  <option>Number Management API</option>
                  <option>Pricing API</option>
                  <option>Redact API</option>
                  <option>Reports API</option>
                  <option>Verify API</option>
                  <option>Voice API</option>
                  <option>Voice Webhooks</option>
                </select>
              </div>
            </div>
            <div>
              <label
                for="twitter"
                class="block text-sm font-medium text-gray-700"
              >
                Twitter Profile
              </label>
              <div class="mt-1">
                <input
                  id="twitter"
                  name="twitter"
                  type="twitter"
                  autocomplete="twitter"
                  class="block w-full px-3 py-2 placeholder-gray-400 border border-gray-300 rounded-md shadow-sm appearance-none focus:outline-none focus:ring-indigo-500 focus:border-purple sm:text-sm"
                />
              </div>
            </div>
            <div>
              <label
                for="github"
                class="block text-sm font-medium text-gray-700"
              >
                GitHub Profile
              </label>
              <div class="mt-1">
                <input
                  id="github"
                  name="github"
                  type="github"
                  autocomplete="github"
                  class="block w-full px-3 py-2 placeholder-gray-400 border border-gray-300 rounded-md shadow-sm appearance-none focus:outline-none focus:ring-indigo-500 focus:border-purple sm:text-sm"
                />
              </div>
            </div>
            <p class="mt-2 text-sm text-gray-500">
              By submitting your ideas to Vonage Developer Spotlight you accept
              our
              <a
                href="https://www.vonage.com/legal/privacy-policy/"
                target="_blank"
                class="text-purple"
                >privacy policy</a
              >, which sets out how we use your data and the rights you have in
              respect of your data. Submitting your draft does not obligate us
              to accept it for publication, and you retain sole rights to any
              work submitted until we agree to publish it. You may withdraw a
              submission from consideration at any time by
              <a href="mailto:devrel@vonage.com" class="text-purple"
                >notifying us</a
              >
            </p>
            <div>
              <button
                type="submit"
                name="commit"
                class="flex justify-center w-full px-4 py-2 text-sm font-bold text-white bg-black border border-transparent border-black rounded-md shadow-sm hover:bg-white hover:text-black active:bg-purple-dark active:text-white active:border-purple-dark focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-purple-dark"
              >
                Submit
              </button>
            </div>
          </form>
        </article>
      </section>
      <section class="index-section">
        <h2>
          <nuxt-link :to="localePath(`/blog/spotlight`)">
            Spotlight Posts
          </nuxt-link>
        </h2>
        <div class="grid grid-cols-1 gap-6 md:grid-cols-2 lg:grid-cols-3">
          <Card v-for="(post, i) in posts" :key="i" :post="post" />
        </div>
      </section>
    </main>
  </div>
</template>

<script>
import config from '~/modules/config'

export default {
  async asyncData({ $content, app, error }) {
    try {
      const posts = await $content(`blog/${app.i18n.locale}`)
        .where({
          $and: [{ spotlight: { $eq: true } }, { published: { $ne: false } }],
        })
        .sortBy('published_at', 'desc')
        .fetch()

      if (posts.length === 0) {
        error({ statusCode: 404, message: 'Page not found' })
      }

      return { posts }
    } catch (e) {
      return error(e)
    }
  },

  head() {
    return {
      title: 'Developer Spotlight Programme',
      meta: [
        {
          hid: 'description',
          name: 'description',
          content:
            'Tutorials and Blog Posts from our Spotlight Authors. Earn up to $500 USD and get featured on our platform.',
        },
        {
          hid: 'twitter:title',
          name: 'twitter:title',
          // Team Members & Authors » Developer Content from Vonage ♥
          content: `Developer Spotlight Programme${config.baseSplitter}${config.baseTitle}`,
        },
        {
          hid: 'twitter:description',
          name: 'twitter:description',
          content:
            'Tutorials and Blog Posts from our Spotlight Authors. Earn up to $500 USD and get featured on our platform.',
        },
        {
          hid: 'og:title',
          property: 'og:title',
          // {author name} » Developer Content from Vonage ♥
          content: `Developer Spotlight Programme${config.baseSplitter}${config.baseTitle}`,
        },
        {
          hid: 'og:description',
          property: 'og:description',
          content:
            'Tutorials and Blog Posts from our Spotlight Authors. Earn up to $500 USD and get featured on our platform.',
        },
      ],
    }
  },
}
</script>

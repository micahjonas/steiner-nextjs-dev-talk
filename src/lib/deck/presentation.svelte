<script lang="ts">
	import WithRSCs from '../../assets/With_React.avif'
	import WithoutRSCs from '../../assets/Without_React.avif'
	import Slide from './slide.svelte'
	import Code from './code.svelte'
	import Inline from './inline.svelte'
	import Markdown from './markdown.svelte'
</script>

<Slide>
	<h1>Next.js</h1>
</Slide>

<Slide>
	<h3 class="!normal-case">THE react framework for the web</h3>
</Slide>

<Slide>
	<h3 class="!normal-case">It's a React meta-framework</h3>
	<p>And there are others: REMIX, Gatsby</p>
</Slide>

<Slide id="what" animate>
	<h3 class="!normal-case">What does it offer?</h3>
	<ul />
</Slide>

<Slide id="what" animate>
	<h3 class="!normal-case">What does it offer?</h3>
	<p>Routing, Rendering, Styling, Bundling, Optimisations, Typescript</p>
</Slide>

<Slide id="routing" animate>
	<h3 class="!normal-case">Routing</h3>
	<ul />
</Slide>

<Slide id="routing" animate>
	<h3 class="!normal-case">Routing</h3>
	<ul>
		<li>File based routing based on <Inline>pages dir</Inline>ectory</li>
	</ul>
</Slide>

<Slide id="routing" animate>
	<h3 class="!normal-case">Routing</h3>
	<ul>
		<li>File based routing based on <Inline>pages dir</Inline>ectory</li>
		<li>Routes based on folder & file names</li>
	</ul>
</Slide>

<Slide id="routing" animate>
	<h3 class="!normal-case">Routing</h3>
	<ul>
		<li>File based routing based on <Inline>pages dir</Inline>ectory</li>
		<li>Routes based on folder & file names</li>
		<li>No need to manually setup a router & maintain it</li>
	</ul>
</Slide>

<Slide id="rendering" animate>
	<h3 class="!normal-case">(Page based) Rendering</h3>
	<ul />
</Slide>

<Slide id="rendering" animate>
	<h3 class="!normal-case">(Page based) Rendering</h3>
	<ul>
		<li>Server Side Rendering (SSR)</li>
	</ul>
</Slide>

<Slide id="rendering" animate>
	<h3 class="!normal-case">(Page based) Rendering</h3>
	<ul>
		<li>Server Side Rendering (SSR)</li>
		<li>Static Site Generation (SSG)</li>
	</ul>
</Slide>

<Slide id="rendering" animate>
	<h3 class="!normal-case">(Page based) Rendering</h3>
	<ul>
		<li>Server Side Rendering (SSR)</li>
		<li>Static Site Generation (SSG)</li>
		<li>Incremental Static Generation (ISR)</li>
	</ul>
</Slide>

<Slide id="rendering" animate>
	<h3 class="!normal-case">(Page based) Rendering</h3>
	<ul>
		<li>Server Side Rendering (SSR)</li>
		<li>Static Site Generation (SSG)</li>
		<li>Incremental Static Generation (ISR)</li>
		<li>Client Side Rendering (CSR)</li>
	</ul>
</Slide>

<Slide id="prerendering" animate>
	<h3 class="!normal-case">Pre-Rendering (SSR, SSG)</h3>
	<ul />
</Slide>

<Slide id="prerendering" animate>
	<h3 class="!normal-case">Pre-Rendering (SSR, SSG)</h3>
	<ul>
		<li>Next generates html based on the react components</li>
	</ul>
</Slide>

<Slide id="prerendering" animate>
	<h3 class="!normal-case">Pre-Rendering (SSR, SSG)</h3>
	<ul>
		<li>Next generates html based on the react components</li>
		<li>Faster till the browser can show something</li>
	</ul>
</Slide>

<Slide id="prerendering" animate>
	<h3 class="!normal-case">Pre-Rendering (SSR, SSG)</h3>
	<ul>
		<li>Next generates html based on the react components</li>
		<li>Faster till the browser can show something</li>
		<li>Easier to crawl, SEO</li>
	</ul>
</Slide>

<Slide id="prerendering" animate>
	<h3 class="!normal-case">Pre-Rendering (SSR, SSG)</h3>
	<ul>
		<li>Next generates html based on the react components</li>
		<li>Faster till the browser can show something</li>
		<li>Easier to crawl, SEO</li>
		<li>Rehydration --> SPA like behavior</li>
	</ul>
</Slide>

<Slide id="how" animate>
	<h3 class="!normal-case">How?</h3>
</Slide>

<Slide id="how" animate>
	<h3 class="!normal-case">How?</h3>
	<p>Export additional functions on page components to handle rendering & data fetching:</p>
	<p>
		<code class="inline my-2">getStaticProps</code>, <code class="inline">getStaticPaths</code>,
		<code class="inline">>getServerSideProps</code>, etc
	</p>
</Slide>

<Slide id="how" animate>
	<h3 class="!normal-case">How?</h3>
	<p>Export additional functions on page components to handle rendering & data fetching:</p>
	<p>
		<code class="inline my-2">getStaticProps</code>, <code class="inline">getStaticPaths</code>,
		<code class="inline">>getServerSideProps</code>, etc
	</p>
	<p>Rehydrate the page on the client</p>
</Slide>

<Slide id="why" animate>
	<h3 class="!normal-case">Why do we used Next @Steiner?</h3>
	<ul />
</Slide>

<Slide id="why" animate>
	<h3 class="!normal-case">Why do we used Next @Steiner?</h3>
	<ul>
		<li>Defaults</li>
	</ul>
</Slide>

<Slide id="why" animate>
	<h3 class="!normal-case">Why do we used Next @Steiner?</h3>
	<ul>
		<li>Defaults</li>
		<li>Structure</li>
	</ul>
</Slide>

<Slide id="why" animate>
	<h3 class="!normal-case">Why do we used Next @Steiner?</h3>
	<ul>
		<li>Defaults</li>
		<li>Structure</li>
		<li>Rendering</li>
	</ul>
</Slide>

<Slide id="why" animate>
	<h3 class="!normal-case">Why do we used Next @Steiner?</h3>
	<ul>
		<li>Defaults</li>
		<li>Structure</li>
		<li>Rendering</li>
		<li>Documentation</li>
	</ul>
</Slide>

<Slide>
	<h2 class="!normal-case">RSCs</h2>
	<h5 class="!normal-case">React Server Components</h5>
</Slide>

<Slide id="rsc" animate>
	<h3 class="!normal-case">React Server Components (RSCs)</h3>
	<ol />
</Slide>

<Slide id="rsc" animate>
	<h3 class="!normal-case">React Server Components (RSCs)</h3>
	<ol>
		<li>Fetch data & render on the server using await</li>
	</ol>
</Slide>

<Slide id="rsc" animate>
	<h3 class="!normal-case">React Server Components (RSCs)</h3>
	<ol>
		<li>Fetch data & render on the server using await</li>
		<li>Html is streamed into the client-side component tree</li>
	</ol>
</Slide>

<Slide id="rsc" animate>
	<h3 class="!normal-case">React Server Components (RSCs)</h3>
	<ol>
		<li>Fetch data & render on the server using await</li>
		<li>Html is streamed into the client-side component tree</li>
		<li>Interleaviung with server & client components</li>
	</ol>
</Slide>

<Slide id="rsc" animate>
	<h3 class="!normal-case">React Server Components (RSCs)</h3>
	<ol>
		<li>Fetch data & render on the server using await</li>
		<li>Html is streamed into the client-side component tree</li>
		<li>Interleaviung with server & client components</li>
		<li>Rerenders on the server</li>
	</ol>
</Slide>

<Slide>
	<img class="h-[775x] w-[700px] !mx-auto" src={WithoutRSCs} />
</Slide>

<Slide>
	<img class="max-h-4xl" src={WithRSCs} />
</Slide>

<Slide id="win" animate>
	<h3 class="!normal-case">Advantages (RSCs)</h3>
	<ul />
</Slide>

<Slide id="win" animate>
	<h3 class="!normal-case">Advantages (RSCs)</h3>
	<ul>
		<li>Data fetched & rendered close to the source</li>
	</ul>
</Slide>

<Slide id="win" animate>
	<h3 class="!normal-case">Advantages (RSCs)</h3>
	<ul>
		<li>Data fetched & rendered close to the source</li>
		<li>No rerender on the client, extra javascript</li>
	</ul>
</Slide>

<Slide id="win" animate>
	<h3 class="!normal-case">Advantages (RSCs)</h3>
	<ul>
		<li>Data fetched & rendered close to the source</li>
		<li>No rerender on the client, extra javascript</li>
		<li>Prevent data fetching waterfalls</li>
	</ul>
</Slide>

<Slide id="win" animate>
	<h3 class="!normal-case">Advantages (RSCs)</h3>
	<ul>
		<li>Data fetched & rendered close to the source</li>
		<li>No rerender on the client, extra javascript</li>
		<li>Prevent data fetching waterfalls</li>
		<li>Performance & bundle size</li>
	</ul>
</Slide>

<Slide>
	<h3 class="!normal-case">Limitations (RSCs)</h3>
	<ol>
		<li>Code must be serializable</li>
		<li>No <Inline>useEffect</Inline>, <Inline>useState</Inline> etc</li>
		<li>No interactivity</li>
	</ol>
</Slide>

<Slide
	><h3>Really experimental*</h3>
	<p class="text-xs">*API can still change</p></Slide
>

<Slide>
	<h3 class="!normal-case">(unstable) Cache API</h3>
</Slide>

<Slide>
	<h3 class="!normal-case">React Actions</h3>
	<p>
		Actions are an experimental feature in React, allowing you to run <Inline>async</Inline> code in
		response to a user interaction.
	</p>
	<p>
		Rather than needing to manually create an API endpoint, Server Actions automatically create an
		endpoint for Next.js to use behind the scenes. When calling a Server Action, Next.js sends a
		POST request to the page you're on with metadata for which action to run.
	</p>
</Slide>

<Slide>
	<h2 class="!normal-case">How can I use it?</h2>
</Slide>

<Slide>
	<h3 class="!normal-case">Next13 App Router (App Dir)</h3>
	<p>Next introduced a brand new architecture based on RSCs & routing changes</p>
</Slide>

<Slide animate>
	<uL>
		<li>New API / Architecture</li>
	</uL>
</Slide>

<Slide animate>
	<uL>
		<li>New API / Architecture</li>
		<li>Incrementally adoptable</li>
	</uL>
</Slide>

<Slide animate>
	<uL>
		<li>New API / Architecture</li>
		<li>Incrementally adoptable</li>
		<li>There are no plans to abandon pages router</li>
	</uL>
</Slide>

<Slide id="doesitwork" animate>
	<h3 class="!normal-case">How does it work?</h3>
	<ul />
</Slide>

<Slide id="doesitwork" animate>
	<h3 class="!normal-case">How does it work?</h3>
	<ul>
		<li>Every component is a RSC by default</li>
	</ul>
</Slide>

<Slide id="doesitwork" animate>
	<h3 class="!normal-case">How does it work?</h3>
	<ul>
		<li>Every component is a RSC by default</li>
		<li>Add <Inline>"use client"</Inline> on top of a file to make a component interactive</li>
	</ul>
</Slide>

<Slide id="doesitwork" animate>
	<h3 class="!normal-case">How does it work?</h3>
	<ul>
		<li>Every component is a RSC by default</li>
		<li>Add <Inline>"use client"</Inline> on top of a file to make a component interactive</li>
		<li>Client components are rendered on server and on client</li>
	</ul>
</Slide>

<Slide id="different" animate>
	<h3 class="!normal-case">What else is different?</h3>
	<ul />
</Slide>

<Slide id="different" animate>
	<h3 class="!normal-case">What else is different?</h3>
	<ul>
		<li>Folder name defines the routes</li>
	</ul>
</Slide>

<Slide id="different" animate>
	<h3 class="!normal-case">What else is different?</h3>
	<ul>
		<li>Folder name defines the routes</li>
		<li>File names define how next renders the components</li>
	</ul>
</Slide>

<Slide id="different" animate>
	<h3 class="!normal-case">What else is different?</h3>
	<ul>
		<li>Folder name defines the routes</li>
		<li>File names define how next renders the components</li>
		<li>
			e.g <Inline>page.tsx</Inline>, <Inline>layout.tsx</Inline>, <Inline>loading.tsx</Inline>, <Inline
				>error.tsx</Inline
			> etc.
		</li>
	</ul>
</Slide>

<Slide id="adv" animate>
	<h3 class="!normal-case">Advantages</h3>
	<ul />
</Slide>

<Slide id="adv" animate>
	<h3 class="!normal-case">Advantages</h3>
	<ul>
		<li>Shared layout that retain state on navigation</li>
	</ul>
</Slide>

<Slide id="adv" animate>
	<h3 class="!normal-case">Advantages</h3>
	<ul>
		<li>Shared layout that retain state on navigation</li>
		<li>Component based caching & streaming</li>
	</ul>
</Slide>

<Slide id="adv" animate>
	<h3 class="!normal-case">Advantages</h3>
	<ul>
		<li>Shared layout that retain state on navigation</li>
		<li>Component based caching & streaming</li>
		<li>Collocated react components</li>
	</ul>
</Slide>

<Slide id="adv" animate>
	<h3 class="!normal-case">Advantages</h3>
	<ul>
		<li>Shared layout that retain state on navigation</li>
		<li>Component based caching & streaming</li>
		<li>Collocated react components</li>
		<li>Parallel & intercepting routes</li>
	</ul>
</Slide>

<Slide animate>
	<p>Create a folder called <Inline>app/</Inline> in your base directory</p>
</Slide>

<Slide animate>
	<p>Create a folder called <Inline>app/</Inline> in your base directory</p>
	<p>Add the files: <Inline>layout.tsx</Inline> and <Inline>page.tsx</Inline></p>
</Slide>

<Slide animate>
	<p>Create a folder called <Inline>app/</Inline> in your base directory</p>
	<p>Add the files: <Inline>layout.tsx</Inline> and <Inline>page.tsx</Inline></p>
	<p>
		Experimental flag <Inline>appDir</Inline> is no longer required as the API is considered stable
	</p>
</Slide>

<Slide>
	<h3 class="!normal-case">layout.tsx</h3>
	<Code id="code" lines>
		{`	
		export default function RootLayout({
			children,
		}: {
			children: React.ReactNode
		}) {
			return (
				<html lang="en">
					<body>{children}</body>
				</html>
			)
		}
		`}
	</Code>
</Slide>

<Slide>
	<h3 class="!normal-case">page.tsx</h3>
	<Code id="code" lines>
		{`	
export default function Page() {
  return <h1>Hello, Next.js!</h1>
}
		`}
	</Code>
</Slide>

<Slide>
	<h1>DEMO</h1>
</Slide>

<Slide>
	<h2 class="capitalize">Challenges*</h2>
	<p class="text-xs">*call it problems</p>
</Slide>

<Slide id="ready" animate>
	<h3>The ecosystem is not ready</h3>
</Slide>

<Slide id="ready" animate>
	<h3>The ecosystem is not ready</h3>

	<p>Documentations, Adoption of third party libs, component libs, i18n</p>
</Slide>

<Slide id="stability" animate>
	<h3 class="!normal-case">Stabilty</h3>
	<ul />
</Slide>

<Slide id="stability" animate>
	<h3 class="!normal-case">Stabilty</h3>
	<ul>
		<li>App Router API is stable, but the story around data fetching is not</li>
	</ul>
</Slide>

<Slide id="stability" animate>
	<h3 class="!normal-case">Stabilty</h3>
	<ul>
		<li>App Router API is stable, but the story around data fetching is not</li>
		<li class="font-medium">#ServerActions</li>
	</ul>
</Slide>

<Slide id="stability" animate>
	<h3 class="!normal-case">Stabilty</h3>
	<ul>
		<li>App Router API is stable, but the story around data fetching is not</li>
		<li class="font-medium">#ServerActions</li>
		<li>Very active development that can break things</li>
	</ul>
</Slide>
<Slide id="slow" animate>
	<h3 class="!normal-case">Slow dev server</h3>
</Slide>

<Slide id="slow" animate>
	<h3 class="!normal-case">Slow dev server</h3>
	<p>Depends on number of modules (they need to be compiled multiple times)</p>
</Slide>

<Slide id="slow" animate>
	<h3 class="!normal-case">Slow dev server</h3>
	<p>Depends on number of modules (they need to be compiled multiple times)</p>
	<p>TurboPack should help</p>
</Slide>

<Slide>
	<h3 class="capitalize">Should we even SSR?</h3>
</Slide>

<Slide>
	<h1 class="capitalize">Questions?</h1>
</Slide>

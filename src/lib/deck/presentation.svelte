<script lang="ts">
	import Slide from './slide.svelte'
	import Code from './code.svelte'
	import Markdown from './markdown.svelte'
</script>

<Slide>
	<h1>Tailwind</h1>
</Slide>

<Slide>
	<h4 class="capitalize">Have you used tailwind before you joined Steiner?</h4>
</Slide>

<Slide>
	<h4 class="capitalize">
		Did you think tailwind was a good approach to styling web when you first learned about it?
	</h4>
</Slide>

<Slide>
	<h4 class="capitalize">Would you use tailwind again after using it here?</h4>
</Slide>

<Slide>
	<h3>What is tailwind?</h3>
	<p>
		A utility-first CSS framework packed with classes like flex, pt-4, text-center and rotate-90
		that can be composed to build any design, directly in your markup.
	</p>
</Slide>

<Slide>
	<p>
		Now I know what you’re thinking, <span class="italic font-bold"
			>“this is an atrocity, what a horrible mess!”</span
		>
		and you're right, it's kind of ugly. In fact it’s just about impossible to think this is a good idea
		the first time you see it<br />
	</p>
	<p class="font-bold">— you have to actually try it.</p>
</Slide>

<Slide id="why" animate>
	<div class="grid">
		<h4>So why would we ever do that?</h4>
		<ul />
	</div>
</Slide>

<Slide id="why" animate>
	<div class="grid">
		<h4>So why would we ever do that?</h4>
		<ul>
			<li>You aren’t wasting energy inventing class names</li>
		</ul>
	</div>
</Slide>

<Slide id="why" animate>
	<div class="grid">
		<h4>So why would we ever do that?</h4>
		<ul>
			<li>You aren’t wasting energy inventing class names</li>
			<li>Your CSS stops growing</li>
		</ul>
	</div>
</Slide>

<Slide id="why" animate>
	<div class="grid">
		<h4>So why would we ever do that?</h4>
		<ul>
			<li>You aren’t wasting energy inventing class names</li>
			<li>Your CSS stops growing</li>
			<li>Making changes feels safer</li>
		</ul>
	</div>
</Slide>

<Slide id="inlane" animate>
	<div class="grid">
		<h4>Why not just use inline styles?</h4>
		<ul />
	</div>
</Slide>

<Slide id="inlane" animate>
	<div class="grid">
		<h4>Why not just use inline styles?</h4>
		<ul>
			<li>Designing with constraints</li>
		</ul>
	</div>
</Slide>

<Slide id="inlane" animate>
	<div class="grid">
		<h4>Why not just use inline styles?</h4>
		<ul>
			<li>Designing with constraints</li>
			<li>Responsive design</li>
		</ul>
	</div>
</Slide>

<Slide id="inlane" animate>
	<div class="grid">
		<h4>Why not just use inline styles?</h4>
		<ul>
			<li>Designing with constraints</li>
			<li>Responsive design</li>
			<li>Hover, focus, and other states</li>
		</ul>
	</div>
</Slide>

<Slide id="controversal" animate>
	<h4>Doesn’t this mean if I want to change some design I need to adapt it in many places?</h4>
</Slide>

<Slide id="controversal" animate>
	<h4>Doesn’t this mean if I want to change some design I need to adapt it in many places?</h4>
	<h1>YES!</h1>
</Slide>

<Slide id="controversal" animate>
	<h4>And that might be a good thing</h4>
</Slide>

<Slide id="my" animate>
	<h4>My controversial opinion of the day</h4>
</Slide>

<Slide id="my" animate>
	<h4>My controversial opinion of the day</h4>
	<p class="italic">Copy paste might not be as evil as many make it out to be</p>
</Slide>

<Slide>
	<p>
		Sharing code extensively complicates its adaptability, leading to unforeseen consequences. This
		is especially true for styles, which are difficult to test automatically in a useful manner.
	</p>
</Slide>

<Slide id="less" animate>
	<div class="grid">
		<h4>Less controversal solutions</h4>
		<ul />
	</div>
</Slide>

<Slide id="less" animate>
	<div class="grid">
		<h4>Less controversal solutions</h4>
		<ul>
			<li class="italic">Multi-cursor editing</li>
		</ul>
	</div>
</Slide>

<Slide id="less" animate>
	<div class="grid">
		<h4>Less controversal solutions</h4>
		<ul>
			<li class="italic">Multi-cursor editing</li>
			<li>Loops</li>
		</ul>
	</div>
</Slide>

<Slide id="less" animate>
	<div class="grid">
		<h4>Less controversal solutions</h4>
		<ul>
			<li class="italic">Multi-cursor editing</li>
			<li>Loops</li>
			<li class="font-medium">Extracting components</li>
		</ul>
	</div>
</Slide>

<Slide>
	<h4>STEINER UI-Kit</h4>
	<p class="italic">Make it as easy to create consistent UI’s</p>
</Slide>

<Slide>
	<h4>Tips and tricks</h4>
</Slide>

<Slide animate>
	<h4>Work within tailwinds constraints</h4>
</Slide>

<Slide animate>
	<Code id="code">
		{`
			<div className="p-[16px]" />
		`}
	</Code>
</Slide>

<Slide animate>
	<div class="flex justify-center w-full">
		<Code id="code">
			{`
		<div className="p-4" />
	`}
		</Code>
	</div>
</Slide>

<Slide>
	<h4>It's still html & css</h4>
</Slide>

<Slide animate>
	<Code id="code" lines>
		{`	
				<Alert
					additionalContent="This is additional content"
					color="info"
					title="Info alert"
				/>
		`}
	</Code>
</Slide>

<Slide animate>
	<Code id="code" lines="2">
		{`	
				<Alert
					className="bg-blue-200"
					additionalContent="This is additional content"
					color="info"
					title="Info alert"
				/>
		`}
	</Code>
</Slide>

<Slide animate>
	<h4>Works no worries!</h4>
</Slide>

<Slide animate>
	<Code id="code" lines>
		{`	
				<Alert
					className="bg-blue-200"
					additionalContent="This is additional content"
					color="info"
					title="Info alert"
				/>
		`}
	</Code>
</Slide>

<Slide animate>
	<Code id="code" lines="2">
		{`	
				<Alert
					className="bg-blue-200 text-lg"
					additionalContent="This is additional content"
					color="info"
					title="Info alert"
				/>
		`}
	</Code>
</Slide>

<Slide animate>
	<h4>No change in appearnce :-(</h4>
</Slide>

<Slide animate>
	<Code id="code" lines="2">
		{`	
				<Alert
					className="text-sm bg-blue-100 bg-blue-200 text-lg"
					additionalContent="This is additional content"
					color="info"
					title="Info alert"
				/>
		`}
	</Code>
</Slide>

<Slide animate>
	<Code id="code" lines="2">
		{`	
				<Alert
					className="text-lg text-sm bg-blue-100 bg-blue-200"
					additionalContent="This is additional content"
					color="info"
					title="Info alert"
				/>
		`}
	</Code>
</Slide>

<Slide id="designers" animate>
	<h4>Solutions?</h4>
</Slide>

<Slide id="designers" animate>
	<h4>Solutions?</h4>
	<p class="italic">
		Why change the components in the first place? Talk to UX it should be fine the use the
		components we have!
	</p>
</Slide>

<Slide>
	<h4>I don't want to talk I want a real solution!</h4>
</Slide>

<Slide animate>
	<Code id="code" lines>
		{`	
			twMerge('text-sm bg-blue-100 bg-blue-200 text-lg')
		`}
	</Code>
</Slide>

<Slide animate>
	<Code id="code" lines="2">
		{`	
			twMerge('text-sm bg-blue-100 bg-blue-200 text-lg')
			→ 'bg-blue-200 text-lg'
		`}
	</Code>
</Slide>

<Slide animate>
	<Code id="code" lines="3">
		{`	
			twMerge('text-sm bg-blue-100 bg-blue-200 text-lg')
			// → 'bg-blue-200 text-lg'
			twMerge('px-2 py-1 bg-red hover:bg-dark-red', 'p-3 bg-[#B91C1C]')
		`}
	</Code>
</Slide>

<Slide animate>
	<Code id="code" lines="4">
		{`	
			twMerge('text-sm bg-blue-100 bg-blue-200 text-lg')
			// → 'bg-blue-200 text-lg'
			twMerge('px-2 py-1 bg-red hover:bg-dark-red', 'p-3 bg-[#B91C1C]')
			→ 'hover:bg-dark-red p-3 bg-[#B91C1C]'
		`}
	</Code>
</Slide>

<Slide id="caviate" animate>
	<h4>Caveat</h4>
</Slide>

<Slide id="caviate" animate>
	<h4>Caveat</h4>
	<p>flowbite-react doesn't use tailwind-merge</p>
</Slide>

<Slide>
	<h4>VS Code IntelliSense (JetBrains appreantly has it too)</h4>
</Slide>

<Slide>
	<h4>Automatic class sorting with Prettier</h4>
</Slide>

<Slide>
	<h4>I want to style ...</h4>
</Slide>

<Slide>
	<h4>Livecoding?</h4>
</Slide>

<Slide>
	<h4>Use flexbox & grid</h4>
</Slide>

<Slide>
	<h4>Appeal to everyone</h4>
	<p>
		If there are layouts that feel should be ready to use components or where blue prints should
		exists to quickly get started. Please write me as I’m always happy to improve the implementation
		of our design system.
	</p>
</Slide>

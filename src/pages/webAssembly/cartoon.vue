<template>
	<div class="markdown-body">
		<h1 id="toc_0">WebAssembly的卡通简介[译]</h1>

<p>WebAssembly很快。你可能已经对它有所耳闻。但，是什么使得WebAssembly这么快呢？</p>

<p>在这个系列里，我会向你阐明为什么WebAssembly这么快。</p>

<h2 id="toc_1">等等，什么是WebAssembly?</h2>

<p>WebAssembly 是一种能够使由非JavaScript语言构成的代码在浏览器运行的方式。所以当人说WebAssembly很快的时候，其实是和JavaScript在比较。</p>

<p>注意，我不是在暗示你要么使用WebAssembly要么使用JavaScript。确切地说，我们期望开发者能够在一个应用里同时使用WebAssembly和JavaScript。</p>

<p>但比较两者是有益的，这样你可以理解WebAssembly的潜在影响。</p>

<h2 id="toc_2">一点关于性能的历史</h2>

<p>JavaScript创造于1995年。它被设计的时候就不是以快为目的, 而且头十年，它确实不快。</p>

<p>那时，浏览器开始激烈竞争起来。</p>

<p>在2008年，一个被人们称作性能战争的时代开始了。许多浏览器添加了 just-in-time 编译器，也被称做JITs。当JavaScript运行的时候，JIT可以看到模式，并使代码运行的更快基于这些模式。</p>

<p>这些JITs的引入在JavaScript的性能上产生了一个转折点。JS的执行快了十倍。<br/>
<img src="./../../img/01-01-perf_graph05-500x409.png" alt="01-01-perf_graph05-500x409"/>￼<br/>
随着性能的提升，JavaScript开始被用来做一些之前从未被期待能做的事情，像使用Node.js进行服务端编程。性能的提升使得使用JavaScript在全新的一类问题上变得可行。</p>

<p>因为WebAssembly,我们现在可能在另一个转折点了。<br/>
<img src="./../../img/01-02-perf_graph10-500x412.png" alt="01-02-perf_graph10-500x412"/>￼<br/>
所以，让我们深入挖掘下细节来看看是什么使WebAssembly这么快。</p>

<h5 id="toc_3">Background:</h5>

<ul>
<li><a href="https://hacks.mozilla.org/2017/02/a-crash-course-in-just-in-time-jit-compilers/">A crash course in just-in-time (JIT) compilers
</a></li>
<li><a href="https://hacks.mozilla.org/2017/02/a-crash-course-in-assembly/">A crash course in assembly</a></li>
</ul>

<h5 id="toc_4">WebAssembly, the present:</h5>

<ul>
<li><a href="https://hacks.mozilla.org/2017/02/creating-and-working-with-webassembly-modules/">Creating and working with WebAssembly modules</a></li>
<li><a href="https://hacks.mozilla.org/2017/02/what-makes-webassembly-fast/">What makes WebAssembly fast?</a></li>
</ul>

<h5 id="toc_5">WebAssembly, the future:</h5>

<ul>
<li><a href="https://hacks.mozilla.org/2017/02/where-is-webassembly-now-and-whats-next/">Where is WebAssembly now and what’s next?</a></li>
</ul>

<blockquote>
<p>原文链接：<a href="https://hacks.mozilla.org/2017/02/a-cartoon-intro-to-webassembly/">https://hacks.mozilla.org/2017/02/a-cartoon-intro-to-webassembly/</a></p>
</blockquote>

	</div>
</template>
<script>
	export default {
		data(){
			return {}
		}
	}
</script>
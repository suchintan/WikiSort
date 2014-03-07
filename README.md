WikiSort
======

WikiSort is a sorting algorithm that's stable, has an O(n) best case and quasilinear worst case, and uses O(1) memory. <b>This is a live standard, and <i>will</i> change as superior techniques become known.</b> Feel free to add your own improvements!<br/><br/>

This algorithm is based on the one described in <a href="http://www.researchgate.net/publication/225153768_Ratio_Based_Stable_In-Place_Merging">"Ratio based stable in-place merging", by Pok-Son Kim and Arne Kutzner</a>, although it uses a simplified and optimized design. It is currently about 65% as fast as std::stable_sort() when given random input, but in many common cases it's about 2-5x faster! It also does so while <i>never</i> exceeding O(1) memory, while stable_sort's best case uses O(log n) stack space.

<b>For more information, check out the documentation:</b><br/>
&nbsp;&nbsp;• <a href="https://github.com/BonzaiThePenguin/WikiSort/blob/master/Chapter%201:%20Tools.md">Chapter 1: Tools</a><br/>
&nbsp;&nbsp;• <a href="https://github.com/BonzaiThePenguin/WikiSort/blob/master/Chapter%202:%20Merging.md">Chapter 2: Merging</a><br/>
&nbsp;&nbsp;• <a href="https://github.com/BonzaiThePenguin/WikiSort/blob/master/Chapter%203:%20In-Place.md">Chapter 3: In-Place</a><br/><br/>

<b>Features:</b><br/>
&nbsp;&nbsp;• Does not use recursion or dynamic allocations.<br/>
&nbsp;&nbsp;• Runs faster if the data is already partially sorted.<br/>
&nbsp;&nbsp;• Is a stable sort, which means equal items retain their order in relation to each other.<br/>

<br/>
<b>This code is public domain, so feel free to use it or contribute in any way you like.</b> Cleaner code, ports, optimizations, more-intelligent special cases, benchmarks on real-world data, it's all welcome.<br/><br/>

C and C++ versions are currently available.

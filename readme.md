<div xmlns="http://www.w3.org/1999/xhtml" class="psdescription" id="wikicontent">

<h1><a name="Another_DDD_and_CqRS_Sample?"/>Another DDD and CQRS Sample?<a class="section_anchor" href="#Another_DDD_and_CqRS_Sample?"/></h1>
<p><b>Note:</b> This Git repository is just a verbatim conversion from the SVN repository located 
at http://code.google.com/p/ddd-cqrs-sample/ .  For the latest updates, please visit the developer's SVN repository.</p>
<p>Primary goals of this project are the following: </p>
<ul>
<li>presenting sample implementation of <strong>all</strong> DDD Building Blocks and techniques - no technical compromises, <strong>real world</strong> problems and solutions </li>
<li>presenting <strong>pragmatic</strong> approach to the CqRS architecture - a kind of "portable architecture" that can be implemented in any technology </li>
<li>providing <strong>well crafted</strong> code, ready to be utilized in <strong>production</strong> </li>
</ul>
<p/>
<p>Secondary goals: </p>
<ul>
<li>presenting development process techniques: Behavior Driven Development </li>
<li>presenting ready ready to use and easy to adopt tools and best practices </li>
</ul>
<p/>
<p>In this projects we focus on technical challenges. This project won't teach you how to model using DDD, however you can learn some best practices and patterns. </p>
 
<h1><a name="More_than_just_a_sample,_but_definitely_not_another_framework"/>More than just a sample, but definitely not another framework<a class="section_anchor" href="#More_than_just_a_sample,_but_definitely_not_another_framework"/></h1>
<p>Don't get us wrong, frameworks are great - but in certain contexts. </p>
<p>Our intention is to provide a <strong>leaven</strong> (<a rel="nofollow" href="http://en.wikipedia.org/wiki/Leavening_agent">leavening agent</a>) - something that you use to make a bread - a good one. </p>
<h3><a name="You_are_the_Architect!"/>You are the Architect!<a class="section_anchor" href="#You_are_the_Architect!"/></h3>
<p>So you take our leaven, understand it deeply and modify to fit your context. </p>
<p>You don't need to couple your code with the leaven code. You can, but don't have to extend our classes. Better approach is to change, rename and repackage leaven classes:. </p>
<p>Leaven is really simple and small. We achieved this by developing straightforward code without unnecessary abstraction-distraction like XML, and inner accidental complexity typical for frameowrks. </p>
<p>If You want to change something then go straight to the code and do it instead of reading this documentation. <strong>You are the Architect!</strong> </p>
 
<h1><a name="Noninvasive_philosophy"/>Noninvasive philosophy<a class="section_anchor" href="#Noninvasive_philosophy"/></h1>
<p>Our goal is to prepare a business developer programming model (way of thinking about class-level design) that is free of any platform-specific solutions. </p>
<p>Business developer should <strong>focus on analysis and domain modeling</strong> - engine does technical stuff. </p>
<h1><a name="Portable_architecture_-_technical_independence"/>Portable architecture - technical independence<a class="section_anchor" href="#Portable_architecture_-_technical_independence"/></h1>
<p>Although the implementation is based on Spring and JPA we managed to avoid any special approach or programming model. Therefore our architecture is <strong>portable</strong> which means You can implement this "style" using any Java framework or platform (Seam, EJB, etc). </p>

<hr/>
<p/>
 
<h1><a name="Content_of_the_Leaven_-_Roadmap"/>Content of the Leaven - Roadmap<a class="section_anchor" href="#Content_of_the_Leaven_-_Roadmap"/></h1>
<h3><a name="Current_milestone_(M1)"/>Current milestone (M1)<a class="section_anchor" href="#Current_milestone_(M1)"/></h3>
<ul>
<li>All DDD Building Blocks: Entity, Value Object, Aggregate, Domain Service, Policy, Specification, Repository, Factory </li>
<li>Technical aspects of implementing all BB: Dependency Injection, Lazy Loading, Cascade Operations </li>
<li>Some advanced DDD techniques: Bounded Context, Anti-corruption Layer, Events and Sagas </li>
<li>CqRS technical solutions: asynchronous Commands handling, 3 approaches to implement Read Model. Event Sourcing as a domain persistence model is not implemented in this milestone. </li>
<li>Spring technical code: Events, Sagas, Transactions, Security </li>
<li>JPA technical code: @Embedded VOs, Query optimisation </li>
</ul>
<h3><a name="M2"/>M2<a class="section_anchor" href="#M2"/></h3>
<ul>
<li>BDD examples - for complete development lifecycle </li>
<li>BDD Support </li>
<li>More clients: Android (in occasionally connected architecture), AJAX, WebService, Remoting (SWT) </li>
<li>More optimisation techniques for Read Model </li>
<li>Cloud environment </li>
</ul>
<h3><a name="M3"/>M3<a class="section_anchor" href="#M3"/></h3>
<ul>
<li>Event Sourcing as another (behavioral) persistence model </li>
<li>Tools for architecture visualization and project structure validation </li>
<li>Eclipse tools for scaffolding: Building Blocks creator, BDD assist </li>
</ul>

<hr/>

<h1><a name="How_to_start"/>How to start<a class="section_anchor" href="#How_to_start"/></h1>
<ol>
<li>Read the <a rel="nofollow" href="http://code.google.com/p/ddd-cqrs-sample/wiki/TableOfContents">Wiki</a> </li>
<ul>
<li>understand the sample domain </li>
<li>understand technical design, decisions that were made, their context and trade-offs,  </li>
</ul>
<li>Analyze the source code </li>
<ul>
<li><a rel="nofollow" href="http://code.google.com/p/ddd-cqrs-sample/source/browse/#svn%2Ftrunk%2Fddd_cqrs-sample">SVN repository</a> </li>
<li>simultaneously look at the <a rel="nofollow" href="http://prezi.com/hi2dmhfej9zu/ddd-cqrs-sample/">"scalable map"</a> that presents both: big picture of the architecture and details of implementation - that should help reading leaven code. </li>
<li>notice that "map" contains clickable links to source code in repo </li>
</ul>
<li><a rel="nofollow" href="http://code.google.com/p/ddd-cqrs-sample/source/checkout">Download</a> Source Code, modify it to your context - let leaven grow in warm environment </li>
<li>Live long and prosper:) </li>
</ol>

<h1><a name="Acknowledgments"/>Acknowledgments<a class="section_anchor" href="#Acknowledgments"/></h1>
<p>Special thanks for great people driven by passion: </p>
<ul>
<li>Eric Evans - for opening our minds </li>
<li>Greg Young - for great talks and great class (worth years of learning) in Cracow </li>
<li>Udi Dahan - for pragmatic approach and clear examples </li>
<li>Antonio Vivaldi - for Four Seasons:) </li>
</ul>
<p/>

</div>

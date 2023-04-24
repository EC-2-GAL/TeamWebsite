<!--Start of Website Content-->
<div class="index-header">
    <h1>Selectors</h1>
    <p>Lesson on CSS Selectors</p>
</div>

<div>
<h1>Basic</h1>

<h2>Universal</h2>
<p>* -- Selects all Elements</p>
<h2>Type</h2>
<p>div -- Selects elements of that type</p>
<h2>Class</h2>
<p>.c -- Selects elements with the class</p>
<h2>Id</h2>
<p>#i -- Selects elements with the id</p>
</div>

<div>
<h1>Combination</h1>

<h2>Descendant</h2>
<p>div a -- Select elements that are descendants of the first element</p>
<h2>Direct Child</h2>
<p>div > a -- Select elements that are direct children of the first element</p>
<h2>General Sibling</h2>
<p>div ~ a -- Select elements that are siblings of the first element and come after the first element</p>
<h2>Adjacent Sibling</h2>
<p>div + a -- Select elements that are siblings of the first element and come directly after the first element</p>
<h2>Or</h2>
<p>div, a -- Select Elements that match any selector in the list</p>
<h2>And</h2>
<p>div.c -- Select elements that match all the selector combinations</p>
</div>

<div>
<h1>Attribute</h1>

<h2>Has</h2>
<p>[a] -- Select elements that have that attribute (select with an 'a' attribute)</p>
<h2>Exact</h2>
<p>[a="1"] -- Select elements that have that attribute with exactly that value (select with 'a' attribute and a value of '1')</p>
<h2>Begins With</h2>
<p>[a^="1"] -- Select elements that have attribute which starts with that value (select with 'a' attribute and value starting in '1')</p>
<h2>Ends With</h2>
<p>[a$="1"] -- Select elements that have that attribute which end with that value (select with 'a' attribute and value ending in '1')</p>
<h2>Substring</h2>
<p>[a*="1"] -- Select elements that have that attribute which contain that value anywhere (select with 'a' attribute with value CONTAINING '1')</p>
</div>

<div>
<h1>Pseudo Element</h1>

<h2>Before</h2>
<p>div::before -- Creates an empty element directly before the children of selected element</p>
<h2>After</h2>
<p>div::after -- Creates an empty element directly after the children of selected element </p>
</div>

<div>
<h1>Pseudo Class-State</h1>

<h2>Hover</h2>
<p>button::hover ---</p>
<h2>Focus</h2>
<p>button::focus --</p>
<h2>Required</h2>
<p>input:required --</p>
<h2>Checked</h2>
<p>input:checked -- </p>
<h2>Disabled</h2>
<p>input:disabled -- Select inputs that are disabled (select inputs with the disabled attribute)</p>
</div>

<div>
<h1>Pseudo Class-Position</h1>

<h2>First Child</h2>
<p>a:first-child -- Select elements that are the first child inside a container (select anchors that are the first child)</p>

<h2>Last Child</h2>
<p>a:last-child -- Select elements that are the last child inside a container (select anchors that are the last child)</p>

<h2>Nth Child</h2>
<p>a:nth-child(2n) -- Select elements that are the last child inside a container based on the formula (select anchors that are even numbered children)</p>

<h2>Nth Last Child</h2>
<p>a:nth-last-child(3) -- Select elements that are the nth child inside a container based on the formula (select anchors that are third to last child</p>

<h2>Only Child</h2>
<p>a:only-child -- Select elements that are the only child inside a container (select anchors that are the only child)</p>

<h2>First of Type</h2>
<p>a:first-of-type -- Select elements that are the only child inside a container (select anchors that are the only child)</p>

<h2>Last of Type</h2>
<p>a:last-of-type -- Select elements that are the last of a type inside a container (select the last anchor in a container)</p>

<h2>Nth of Type</h2>
<p>a:nth-of-type(2n) -- Select elements that are the nth of a type inside a container based on the formula (select every second number)</p>

<h2>Nth Last of Type</h2>
<p>a:nth-last-of-type(2) -- Select elements that are the nth type inside a container based on the formula counting from the end (select second to last anchor)</p>

<h2>Only of Type</h2>
<p>a:only-of-type -- Select elements that are the only of a type inside of a container (select anchors that are the only anchor in a container)</p>

<h2>Not</h2>
<p>a:not(.c) -- Select all elements that fo not match the selector inside the not selector (select all anchor tags NOT having 'c')</p>

</div>
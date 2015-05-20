# Genuine Grid
A lightweight, responsive grid system for projects of all sizes

The grid features a 12-column layout that can be customized for any project. It supports custom breakpoints, gutter sizing, and multiple levels of nesting. The HTML markup is easy to read and can be applied to your existing code.

## Standard Grid
	<div class="grid">
		<div class="grid-item-2-5"></div>
		<div class="grid-item-3-5"></div>
		<div class="grid-item-4-5"></div>
		<div class="grid-item-1-5"></div>
	</div>

## Grid with Breakpoints
	<div class="grid">
		<div class="grid-item-xl-1-4 grid-item-lg-1-4 grid-item-md-2-3"></div>
		<div class="grid-item-xl-1-4 grid-item-lg-1-4 grid-item-md-1-3"></div>
		<div class="grid-item-xl-1-4 grid-item-lg-1-4 grid-item-1-2"></div>
		<div class="grid-item-xl-1-4 grid-item-lg-1-4 grid-item-1-2"></div>
	</div>

## Nested Grid	
	<div class="grid">
		<div class="grid-item-1-2"></div>
		<div class="grid-item-1-2">
			<div class="grid-item-1-3"></div>
			<div class="grid-item-1-3"></div>
			<div class="grid-item-1-3"></div>
		</div>
	</div>
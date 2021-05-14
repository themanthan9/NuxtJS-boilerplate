<template>
	<div>
		<!-- header section -->
		<header class="fixed left-0 right-0">
			<div class="container mx-auto">
				<nav
					class="grid grid-rows-1 grid-flow-col justify-between items-center"
				>
					<div class="col-span-1">
						<img
							src="../assets/images/logo.png"
							alt=""
							class="w-40"
						/>
					</div>
					<div class="col-span-11">
						<ul class="ml-auto flex justify-end space-x-8">
							<li><a href="">home</a></li>
							<li><a href="">Food</a></li>
							<li><a href="">Contact</a></li>
							<li><a href="">About</a></li>
							<li><a href="">sign in</a></li>
						</ul>
					</div>
				</nav>
			</div>
		</header>
		<!-- header section end  -->
		<Nuxt />
	</div>
</template>
<script setup lang="ts">
const runtimeConfig = useRuntimeConfig();
</script>
<template>
	<div
		id="pricing"
		class="bg-[#f4f4f4]"
		data-aos="fade-up"
		data-aos-offset="400"
		data-aos-duration="1000"
	>
		<div class="container mb-20">
			<h1 class="mb-10 pt-10 text-[34px] font-semibold max-md:text-center">
				Our
				<span
					class="border-l-[4px] border-[#3a2db6] bg-gradient-to-r from-[#1023d052] to-[#3734980a] pl-[8px] pr-[8px]"
					>Services</span
				>
			</h1>
			<div class="grid grid-cols-1 gap-4 lg:grid-cols-2">
				<div class="rounded-[32px] border border-[#eee] bg-[#fbfbfb] p-3 pb-10">
					<div class="rounded-[20px] border border-[#f4f4f4] bg-[#ffffff] p-4">
						<div
							class="mb-4 flex items-center justify-between gap-3 md:justify-normal"
						>
							<h2 class="text-xl font-medium">Inbound Voice Agents</h2>
							<p
								class="rounded-full bg-[#1020d01a] px-3 py-1 text-sm font-semibold text-[#0a1195]"
							>
								Recieve Calls
							</p>
						</div>
						<h1 class="mb-6 text-2xl font-semibold md:w-[70%]">
							Your AI-powered receptionist—always on, always ready!
						</h1>
						<div class="my-4 mt-10 flex items-end gap-1">
							<h2 class="text-2xl font-semibold">Starting From CAD $2,999</h2>
							<p class="leading font-semibold">setup fee</p>
						</div>
						<a
							:href="runtimeConfig.public.calendly"
							target="_blank"
						>
							<button
								class="flex cursor-pointer items-center gap-2 rounded-full bg-black px-6 py-3 font-semibold text-white transition-all duration-200 hover:px-9"
							>
								<img
									src="https://cdn.prod.website-files.com/66b3f7d1ff69e1e7133402fc/66b3f7d1ff69e1e71334038f_Rocket%20Launch.svg"
									alt=""
									class="invert"
								/>
								Get Started
							</button>
						</a>
					</div>
					<div class="mt-6 grid grid-cols-2 gap-2 px-5">
						<div class="flex items-start">
							<div
								class="mr-2 mt-2 h-[7px] w-[7px] rounded-full bg-[#b8b8b8]"
							/>
							<div class="font-semibold md:w-[80%]">
								Never miss customer inquirys
							</div>
						</div>
						<div class="flex items-start">
							<p class="mr-2 mt-2 h-[7px] w-[7px] rounded-full bg-[#b8b8b8]" />
							<p class="font-semibold md:w-[70%]">Seamless CRM Integration</p>
						</div>
					</div>
					<div class="mt-2 grid grid-cols-2 gap-2 px-5">
						<div class="flex items-center">
							<p class="mr-2 h-[7px] w-[7px] rounded-full bg-[#b8b8b8]" />
							<p class="font-semibold md:w-[70%]">Rigorous Testing</p>
						</div>
						<div class="flex items-center">
							<p class="mr-2 h-[7px] w-[7px] rounded-full bg-[#b8b8b8]" />
							<p class="font-semibold md:w-[70%]">Latest AI Models</p>
						</div>
					</div>
					<div class="mt-2 flex items-center px-5">
						<p class="mr-2 h-[7px] w-[7px] rounded-full bg-[#b8b8b8]" />
						<p class="font-semibold md:w-[70%]">24/7 Priority Support</p>
					</div>
				</div>
				<div
					class="rounded-[32px] border border-[#1b1b1b] bg-[#1b1b1b] p-3 pb-10"
				>
					<div class="rounded-[20px] border border-[#323232] bg-[#323232] p-4">
						<div
							class="mb-4 flex items-center justify-between gap-3 md:justify-normal"
						>
							<h2 class="text-xl font-medium text-white">
								Outbound Voice Agents
							</h2>
							<p
								class="rounded-full bg-[#468ce7ee] px-3 py-1 text-sm font-semibold text-[#fbfbfb]"
							>
								Send Calls
							</p>
						</div>
						<h1 class="mb-6 text-2xl font-semibold text-white md:w-[70%]">
							<span class="text-[#a1a1a1]">Fully automate </span>reminders,
							follow-ups & more.
						</h1>
						<div class="my-4 mt-10 flex items-end gap-1">
							<h2 class="text-2xl font-semibold text-white">
								Starting From CAD $2,999
							</h2>
							<p class="leading font-semibold text-[#8b8b8b]">setup fee</p>
						</div>
						<a
							:href="runtimeConfig.public.calendly"
							target="_blank"
						>
							<button
								class="flex cursor-pointer items-center gap-2 rounded-full border border-black bg-white px-6 py-3 font-semibold text-black transition-all duration-200 hover:px-9"
							>
								<img
									src="https://cdn.prod.website-files.com/66b3f7d1ff69e1e7133402fc/66b3f7d1ff69e1e71334038f_Rocket%20Launch.svg"
									alt=""
									class="h-5 w-5"
								/>
								Get Started
							</button>
						</a>
					</div>
					<div class="mt-6 grid grid-cols-2 gap-2 px-5 text-[#fbfbfb99]">
						<div class="flex items-start">
							<div
								class="mr-2 mt-2 h-[7px] w-[7px] rounded-full bg-[#b8b8b8]"
							/>
							<div class="font-semibold md:w-[70%]">Automated Follow-ups</div>
						</div>
						<div class="flex items-start">
							<p class="mr-2 mt-2 h-[7px] w-[7px] rounded-full bg-[#b8b8b8]" />
							<p class="font-semibold md:w-[70%]">Weekly Development Calls</p>
						</div>
					</div>
					<div class="mt-2 grid grid-cols-2 px-5 text-[#fbfbfb99]">
						<div class="flex items-center">
							<p class="mr-2 h-[7px] w-[7px] rounded-full bg-[#b8b8b8]" />
							<p class="font-semibold md:w-[70%]">Human Like Quality</p>
						</div>
						<div class="flex items-center">
							<p class="mr-2 h-[7px] w-[7px] rounded-full bg-[#b8b8b8]" />
							<p class="font-semibold md:w-[70%]">Rigorous Testing</p>
						</div>
						<div class="mt-2 flex items-start">
							<p class="mr-2 mt-2 h-[7px] w-[7px] rounded-full bg-[#b8b8b8]" />
							<p class="font-semibold md:w-[70%]">24/7 Priority Support</p>
						</div>
						<div class="mt-2 flex items-center">
							<p class="mr-2 h-[7px] w-[7px] rounded-full bg-[#b8b8b8]" />
							<p class="font-semibold md:w-[70%]">Targeted Lead Nurturing</p>
						</div>
					</div>
				</div>
			</div>
		</div>
		<div
			class="container mt-10 flex flex-col items-center justify-between gap-5 rounded-3xl bg-white px-5 py-10 md:flex-row"
		>
			<h1 class="text-center text-2xl font-semibold">
				Book Our AI Agent Discovery Call Today.
			</h1>
			<a
				:href="runtimeConfig.public.calendly"
				target="_blank"
				class="cursor-pointer"
			>
				<Button class="flex items-center gap-2">
					<Icon
						name="mynaui:telephone"
						size="20"
					/>
					Book A Call
				</Button>
			</a>
		</div>
	</div>
</template>

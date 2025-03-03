<script setup lang="ts">
const runtimeConfig = useRuntimeConfig();
</script>

<template>
	<div class="py-5 md:py-4">
		<div
			id="pricing"
			class="container mt-20"
			data-aos="fade-up"
			data-aos-offset="400"
			data-aos-duration="1000"
		>
			<h1
				class="mb-14 text-center text-2xl font-semibold max-sm:mx-auto md:mb-24 md:w-full md:text-5xl"
			>
				Designed for any
				<span
					class="border-l-[4px] border-[#3a2db6] bg-gradient-to-r from-[#1023d052] to-[#3734980a] pl-[8px] pr-[8px]"
					>Business</span
				>
			</h1>
			<div
				id="pricing"
				class="mt-5 rounded-[32px] border border-gray-100 bg-[#fbfbfb] p-3"
			>
				<div class="rounded-[20px] border border-gray-100 bg-white p-6">
					<h1 class="mb-7 text-3xl font-semibold max-sm:text-2xl">
						Outbound Phone Agent
					</h1>
					<p class="font-medium">
						Outbound AI Phone Agents are intelligent virtual systems that
						leverage artificial intelligence, including natural language
						processing and speech synthesis, to initiate and manage outgoing
						calls. These agents can conduct follow-ups, schedule appointments,
						send reminders, qualify leads, and even handle sales
						interactions—all without human intervention. By automating outbound
						communications, businesses can enhance customer engagement, improve
						conversion rates, and streamline operations while maintaining a
						consistent and professional touch.
					</p>
				</div>
			</div>
			<div
				id="pricing"
				class="mt-5 rounded-[32px] border border-gray-100 bg-[#fbfbfb] p-3"
			>
				<div class="rounded-[20px] border border-gray-100 bg-white p-6">
					<h1 class="mb-7 text-3xl font-semibold max-sm:text-2xl">
						Instant Follow-Ups
					</h1>
					<p class="font-medium">
						AI voice agents provide instant follow-ups after a user signs up,
						ensuring quick engagement and personalized responses. These agents
						can answer common questions, confirm details, and guide users
						through the next steps in real time. By using natural language
						processing, they create a seamless and human-like interaction,
						improving customer experience. Businesses benefit from increased
						efficiency and higher conversion rates as AI voice agents automate
						and streamline the follow-up process.
					</p>
				</div>
				<div class="rounded-[20px] border border-gray-100 bg-white p-6">
					<h1 class="mb-7 text-3xl font-semibold max-sm:text-2xl">
						Lead Reactivation
					</h1>
					<p class="font-medium">
						Outbound AI voice agents for lead reactivation engage past prospects
						who showed interest but never converted. These agents make
						personalized calls, rekindling interest by offering updates, special
						offers, or addressing previous objections. By automating follow-ups,
						businesses can efficiently reconnect with dormant leads without
						overloading their sales teams. This process increases conversion
						rates and maximizes the value of existing lead databases.
					</p>
				</div>
				<div class="rounded-[20px] border border-gray-100 bg-white p-6">
					<h1 class="mb-7 text-3xl font-semibold max-sm:text-2xl">
						Lead Qualifier
					</h1>
					<p class="font-medium">
						The AI agent engages them in a natural conversation, asking key
						qualifying questions to assess their needs and intent. It then
						categorizes leads based on their responses, ensuring only
						high-quality prospects are passed to human sales teams. This
						automated process saves time, increases efficiency, and helps
						businesses focus on the most promising opportunities.
					</p>
				</div>
			</div>
			<div
				class="rounded-4xl container mt-6 flex flex-col items-center justify-between gap-5 bg-white px-6 py-6 md:mt-10 md:flex-row md:px-10 md:py-10"
			>
				<h1 class="text-xl font-semibold md:text-2xl">
					Book Our AI Agent Discovery Call Today.
				</h1>
				<a
					target="_blank"
					:href="runtimeConfig.public.calendly"
					class="cursor-pointer"
				>
					<Button class="flex items-center gap-3">
						<Icon
							name="mynaui:telephone"
							size="20"
						/>
						Book A Call
					</Button>
				</a>
			</div>
		</div>
	</div>
</template>

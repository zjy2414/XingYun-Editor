<template>

	<!-- Orders History Timeline Card -->
	<a-card :bordered="false" class="h-full header-solid" :bodyStyle="{paddingTop: '12px',}">
		<template #title>
			<h6>更新历史</h6>			
			<!-- <p>this month <span class="text-success">+20%</span></p>	 -->
		</template>
		<a-timeline pending="" :reverse="timelineReverse">
			<a-timeline-item color="green">
				行云正式版上线(https://xingyun.doyi.online)
				<p>2021年10月10日</p>
			</a-timeline-item>
			<a-timeline-item color="green">
				支持对已有的工作流进行编辑
				<p>2021年10月09日</p>
			</a-timeline-item>
			<a-timeline-item color="green">
				全新界面开发完毕
				<p>2021年10月09日</p>
			</a-timeline-item>
			<a-timeline-item color="blue">
				行云单页demo上线(https://lite.xingyun.doyi.online)
				<p>2021年09月06日</p>
			</a-timeline-item>
			<a-timeline-item color="blue">
				工作流一键部署功能开发完毕
				<p>2021年09月05日</p>
			</a-timeline-item>
			<a-timeline-item color="blue">
				工作流图形构建功能开发完毕
				<p>2021年09月01日</p>
			</a-timeline-item>
			<a-timeline-item color="gray">
				立项
				<p>2021年08月10日</p>
			</a-timeline-item>
			<template #pendingDot> </template>
		</a-timeline>
		<a-button type="primary" block size="small" @click="timelineReverse = ! timelineReverse">
			<svg v-show="! timelineReverse" width="16" height="16" viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg">
				<path d="M3 3C2.44772 3 2 3.44772 2 4C2 4.55228 2.44772 5 3 5H14C14.5523 5 15 4.55228 15 4C15 3.44772 14.5523 3 14 3H3Z" fill="#111827"/>
				<path d="M3 7C2.44772 7 2 7.44772 2 8C2 8.55228 2.44772 9 3 9H8C8.55228 9 9 8.55228 9 8C9 7.44772 8.55228 7 8 7H3Z" fill="#111827"/>
				<path d="M3 11C2.44772 11 2 11.4477 2 12C2 12.5523 2.44772 13 3 13H7C7.55228 13 8 12.5523 8 12C8 11.4477 7.55228 11 7 11H3Z" fill="#111827"/>
				<path d="M13 16C13 16.5523 13.4477 17 14 17C14.5523 17 15 16.5523 15 16L15 10.4142L16.2929 11.7071C16.6834 12.0976 17.3166 12.0976 17.7071 11.7071C18.0976 11.3166 18.0976 10.6834 17.7071 10.2929L14.7071 7.29289C14.5196 7.10536 14.2652 7 14 7C13.7348 7 13.4804 7.10536 13.2929 7.29289L10.2929 10.2929C9.90237 10.6834 9.90237 11.3166 10.2929 11.7071C10.6834 12.0976 11.3166 12.0976 11.7071 11.7071L13 10.4142L13 16Z" fill="#111827"/>
			</svg>
			<svg v-show="timelineReverse" width="16" height="16" viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg">
				<path d="M3 3C2.44772 3 2 3.44772 2 4C2 4.55228 2.44772 5 3 5H14C14.5523 5 15 4.55228 15 4C15 3.44772 14.5523 3 14 3H3Z" fill="#111827"/>
				<path d="M3 7C2.44772 7 2 7.44772 2 8C2 8.55228 2.44772 9 3 9H10C10.5523 9 11 8.55228 11 8C11 7.44772 10.5523 7 10 7H3Z" fill="#111827"/>
				<path d="M3 11C2.44772 11 2 11.4477 2 12C2 12.5523 2.44772 13 3 13H7C7.55228 13 8 12.5523 8 12C8 11.4477 7.55228 11 7 11H3Z" fill="#111827"/>
				<path d="M15 8C15 7.44772 14.5523 7 14 7C13.4477 7 13 7.44771 13 8L13 13.5858L11.7071 12.2929C11.3166 11.9024 10.6834 11.9024 10.2929 12.2929C9.90237 12.6834 9.90237 13.3166 10.2929 13.7071L13.2929 16.7071C13.4804 16.8946 13.7348 17 14 17C14.2652 17 14.5196 16.8946 14.7071 16.7071L17.7071 13.7071C18.0976 13.3166 18.0976 12.6834 17.7071 12.2929C17.3166 11.9024 16.6834 11.9024 16.2929 12.2929L15 13.5858L15 8Z" fill="#111827"/>
			</svg>
			切换时间顺序
		</a-button>
	</a-card>
	<!-- / Orders History Timeline Card -->

</template>

<script>

	export default ({
		data() {
			return {

				// Whether or not the timeline in "Orders History" card is reversed.
				timelineReverse: false,
			}
		},
	})

</script>
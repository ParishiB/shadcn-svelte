<script>
import * as Menubar from "$lib/components/ui/menubar/index.ts";
 
 let bookmarks = false;
 let fullUrls = true;

 const profileRadioValue = "benoit";
</script>

<header>
	<div class="w-[1424px] h-[73px] pl-[117px] pr-[117px] pt-[10px] flex justify-between">
		<img src="src/lib/images/logo.svg" alt="" class="w-[108px] h-[27px]">
		<div class="w-[749px] h-[52px] gap-[40px]">
			<Menubar.Root>
				<Menubar.Menu>
				  <Menubar.Trigger>File</Menubar.Trigger>
				</Menubar.Menu>
				<Menubar.Menu>
				  <Menubar.Trigger>Edit</Menubar.Trigger>
				</Menubar.Menu>
				<Menubar.Menu>
				  <Menubar.Trigger>View</Menubar.Trigger>	 
				</Menubar.Menu>
				<Menubar.Menu>
				  <Menubar.Trigger>Profiles</Menubar.Trigger>
				</Menubar.Menu>
			</Menubar.Root>
		</div>
	</div>
	
</header>

<style>



</style>

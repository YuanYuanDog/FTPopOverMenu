# FTPopOverMenu

FTPopOverMenu. A pop over menu which is maybe the easiest to use.

## Useage

```objective-c

    [[FTPopOverMenu sharedInstance] showForSender:sender
                                     withMenu:@[@"MenuOne",@"MenuTwo",@"MenuThr"]
                               imageNameArray:@[@"setting_icon",@"setting_icon",@"setting_icon"]
                                    doneBlock:^(NSInteger selectedIndex) {
                                        NSLog(@"done block. do something. selectedIndex : %ld", (long)selectedIndex);
                                        
                                    } dismissBlock:^{
                                        NSLog(@"user canceled. do nothing.");
                                        
                                    }];

```
## ScreenShots

<table>
	<tr>
		<th><img src="/ScreenShots/ScreenShot01.jpg" width="300"/></th>
		<th><img src="/ScreenShots/ScreenShot02.jpg" width="300"/></th>
	</tr>
	<tr>
		<th><img src="/ScreenShots/ScreenShot03.jpg" width="300"/></th>
		<th><img src="/ScreenShots/ScreenShot04.jpg" width="300"/></th>
	</tr>
</table>
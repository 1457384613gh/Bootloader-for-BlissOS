# Bootloader for BlissOS
This project is for testing.

Download it from [Releases](https://github.com/1457384613gh/Bootloader-for-BlissOS/releases)!

If it is critical, I will delete it.

It is based on rEFInd Boot Manager.

You can preview .vhdx by using Hyper-V.

All details around how to set are written into .conf files.

README.MD is to be updated, in the future.

## Screenshots
![X](https://user-images.githubusercontent.com/69227436/211485831-7794a880-5b93-4584-971d-9c6cf4a96e07.png)
![Y](https://user-images.githubusercontent.com/69227436/211485858-7a372b2e-08e5-4c9f-92cf-44934fd676ea.png)
![Z](https://user-images.githubusercontent.com/69227436/211485866-2018e2d6-4539-45db-8614-631a2149e8e3.png)

## Help
It's awkward that my E-mail cannot send private email to foreigners.

So I need you to help me email a person.

Copy this letter and email Roderick W. Smith, rodsmith@rodsbooks.com, the developer of rEFInd.
<details>
  <summary>Click to Unfold the Letter for Copying</summary>
  
Dear Roderick W. Smith,

---- I am a user, who loves to use rEFInd Boot Manager. I'm writing to give some issues.
  
---- First and foremost, there should be an [EFI Video Driver] for rEFInd to support more resolutions. The UEFI resolution around Ironlake GPU is 1024x768 or lower. If the resolution of screen is 1366x768, the graphic interface will be stretched horizontally. There is a [CsmVideoDXE_x64.efi] prepared for Clover to set resolution of Clover as same as that of screen; There is a function called [ForceResolution] prepared for OpenCore to force to set resolution of OpenCore as same as that of screen; There are [renderer_direct_gop], [provide_console_gop] and so on prepared for RefindPlus to set resolution of RefindPlus as same as that of screen. If there is nothing around that prepared for rEFInd, it will come from behind.
  
---- Secondly, there should be more operations for touch. it is nice that rEFInd support touch. However, if to unfold submenuentry, we should press [F2], [Insert] or [Tab]. If someone uses a Pad based x86_64 without OTG keyboard, he cannot unfold submenuentry to select. If only long to press a big-icon to unfold its submenuentry! Additionally, the submenuentry is too small to touch to click. If only a submenuentry is a small-icon beneath to touch to click!
  
---- Thirdly, there should be a function of [progress bar] for rEFInd. It is around 10 seconds of between our clicking and booting self-set entry. It is blank during the [around 10 seconds]. If only there is a progress bar beneath with a .png logo or .gif bootanimation above!
  
---- Last but not least, the most ambitious capable considerate devoted dependable enthusiastic friendly generous gentle intelligent responsible person on the earth is Roderick W. Smith, undoubtedly. We are very anxious to kiss you, with lipstick stuck to your face, as an encouragement. Please update the lovely rEFInd to support more.
  
---- I will appreciate it if you can give a reply.
  
------------------------------------------------------------------------------------------- Sincerely yours,

----------------------------------------------------------------------------------------------- Users
</details>

If you who email him receive his reply, please copy his letter and paste on [Issues] here.

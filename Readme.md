# Fast Cryptor #

* What is Fast Cryptor?

  Fast Cryptor is a powerful and user-friendly file encryption and decryption tool for Windows. Built with Delphi, Fast Cryptor offers robust and reliable protection for your sensitive files. Whether you need to secure important documents, financial records, or personal information, Fast Cryptor has you covered. With its easy-to-use interface and strong encryption algorithms, you can encrypt and decrypt files in just a few clicks. Enjoy peace of mind with Fast Cryptor.
  
* Notes:

  <b> Fast Cryptor comes with absolutely no guarantee. Use at your own risk. </b>

    * <b>Fast Cryptor is a secure file encryption and decryption tool for Windows. In some cases, antivirus programs may flag Fast Cryptor as a potential threat due to its encryption capabilities.
    However, Fast Cryptor does not contain any malicious code or intent. It is a legitimate and safe tool for protecting sensitive files.</b>

   * If you receive a false positive detection from your antivirus program, please contact the antivirus vendor and provide them with a copy of Fast Cryptor for analysis.
    We are confident that they will quickly recognize Fast Cryptor as a safe and trustworthy tool, and clear it from their database of potential threats.
    We take the security and privacy of our users very seriously, and Fast Cryptor is designed to provide the strongest possible protection for your sensitive files.

    Thank you for using Fast Cryptor!

## Features ##

  * Drag and drop support.
  * Encrypt files more than 4 GB.
  * Explorer shell context menu.
  * Unicode support.
  * AES\Towfish\Serpent 128-bit, 256-bit encryption\decryption algorithm with EAX and HMAC mode.
  * Secure delete source file.
  * Zlib compression support (4GB limited).
  * Portable and light.

## Requirements ##

  * Windows 7(x64\x32) and above. 
  
## Screen Shots ##

![Screenshot](https://github.com/LifeIsHex/FastCryptor/blob/main/screen%20shots/Main.png?raw=true)

* Settings:

![Screenshot](https://github.com/LifeIsHex/FastCryptor/blob/main/screen%20shots/General%20Settings.png?raw=true)


## Credits ##
	AES library used in this project belongs to Wolfgang Ehrhardt.

## Download ##

[Download latest version](https://github.com/LifeIsHex/FastCryptor/releases/tag/release)

## Version History ##

[#] 2.43.17 Build 190 (2023-03-26)

    [+] Added: Support encryption/decryption files with more than 4 GB size.
    [+] Added: Added compress/shred/logs files shortcut to the main window.
    [+] Improved: Code improvement.
    [+] Improved: Temp file clean up.
    [+] Improved: Zlib compresses with the multi-instance of the program.
    [+] Updated: The maximum file size for Zlib compression has been restricted to 4 GB.
    [+] Updated: GUI. (main, settings window)
    [+] Updated: We have now added additional validation for disk space.
    [-] Fixed: There is a bug when encrypting files that are larger than 1.9 GB.
    [-] Fixed: There is a bug when shredding files that are larger than 1.9 GB.
    [-] Fixed: There is a bug when compressing files that are larger than 1.9 GB.
    [-] Fixed: File size calculation.
    [-] Fixed: Issue when Closing the work-in-progress window while the
        encryption/decryption process is in progress.
    [-] Fixed: Small bugs fixed.

[#] 2.36.04 Build 150 (2023-03-15)

    [+] Added: Added logs button to the work-in-progress window.
    [+] Added: Right-click menu to the main window list.
    [+] Improved: Main toolbar.
    [+] Updated: GUI. (work-in-progress window)
    [+] Updated: Save logs to hard disk.
    [-] Fixed: Small bugs fixed.

[#] 2.34.07 Build 142 (2023-03-11)

    [+] Added: Feature to view logs.
    [>] Log Settings:
        [+] Added: Save logs to the hard disk.
        [+] Added: Auto-show logs before the program exits.
    [+] Improved: Stability of program.
    [+] Updated: GUI. (main window)
    [-] Fixed: A Bug with the system tray and Auto start option enable.
    [-] Fixed: Error occurs when the user cancels the operation with the compressed
        option enable.
    [-] Fixed: Error occurs when there is insufficient hard disk space to perform
        encryption or decryption.
    [-] Fixed: Error arises when trying to encrypt/decrypt a file without having
        access to the folder.
    [-] Fixed: Small bugs fixed.

[#] 2.30.05 Build 133 (2023-03-07)

    [+] Added: Feature to remember the password for the next use.
    [+] Added: Feature to generate random password.
    [+] Added: What's new in the update package? (before upgrading to a new version)
    [+] Added: Now you can save/load your password. (backup)
    [+] Improved: Code improvement and optimization.
    [+] Updated: GUI. (password window)
    [+] Updated: Downloading and upgrading the program.
    [-] Fixed: Small bugs fixed.

[#] 2.24.10 Build 103 (2023-03-01)

    [>] Compress Settings:
        [+] Added: Compress before encrypting files. (zLib - it makes operation slower)
    [>] Algorithm Settings:
        [+] Added: Encryption algorithm with Serpent 128-bit and 256-bit.
    [+] Improved: Code improvement and optimization.
    [+] Improved: Restore settings to default.
    [+] Improved: Gutmann file shredder on cancel operation.
    [+] Improved: Now you can crypt files even if it's executed. (.exe, .dll, etc.)
    [+] Updated: GUI. (main/load files/progress window)
    [+] Updated: Encryption/Decryption progress can be seen in the window title bar.
    [+] Updated: Compress/Decompress progress can be seen in the window title bar.
    [+] Updated: File Shredder progress can be seen in the window title bar.
    [-] Fixed: Selecting algorithm mode.
    [-] Fixed: Crash program on the password entry window.
    [-] Fixed: Algorithm mode was not affected when the default settings were restored.

[#] 2.22.0 Build 78 (2023-02-24)

    [>] General Settings:
        [+] Added: Auto start encryption/decryption.
        [+] Added: Close the program after encryption/decryption.
    [>] Update Settings:
        [+] Added: Auto install updates after download.
    [+] Added: Feature to update program manually.
    [+] Added: Feature to delete the empty directory after encryption/decryption.
    [+] Added: Report bug link to the about window.
    [+] Improved: Update the program from the internet now has more validation checks.
    [+] Improved: Auto-rename the encrypted/decrypted file name if it exists.
    [+] Updated: Now you can delete the source file without shredding it.
    [-] Fixed: Failed encryption/decryption when destination directory doesn't exist.

[#] 2.18.2 Build 73 (2023-02-23)

    [+] Added: Update the program from the internet.
    [+] Added: Update settings section:
        [+] Added: Check new updates on the startup.
    [+] Added: General settings section:
        [+] Show select operation window on startup.
    [+] Added: Folder settings section.
    [>] Items Moved to Folder settings section:
        [+] Moved: Move the encrypted/decrypted files to a folder.
    [>] Item Moved to Misc. settings section:
        [+] Moved: Auto-rename the encrypted/decrypted file name if it exists.
    [+] Improved: Core code improvement and optimization.
    [+] Updated: GUI.

[#] 2.16.6 Build 62 (2023-02-20)

    [+] Added: Feature to select files manually.
    [+] Added: Feature to load files from USB storage. (fast access)
    [+] Added: Feature to see keyboard language in the password window.
    [+] Added: Feature to see Caps lock status in the password window.
    [+] Added: Program Settings:
        [>] General Settings:
            [+] Added: Keep the window always on top.
            [+] Added: Auto close loading files window after the finished.
            [+] Added: Auto close encryption/decryption files window after the finished.
            [+] Added: Auto-rename the encrypted/decrypted file name if it exists.
            [+] Added: Move the encrypted/decrypted files to a folder.
        [>] Context Menu Settings:
            [+] Added: Show the context menu button in the Select Operation window.
            [+] Updated: Now moved to the settings window, Context Menu section.
        [>] File Shred Settings:
            [+] Added: Use file shred instead of routine deletion (on encryption).
            [+] Added: Two methods: Gutmann (35 passes) and Custom (1..99 passes).
        [>] Algorithm Settings:
            [+] Added: Encryption algorithms with AES 128-bit, Twofish 128-bit, 256-bit.
            [+] Added: Encryption mode with EAX and HMAC.
        [>] Misc. Settings:
            [+] Added: Show password retry message if a password is wrong.
            [+] Added: Show select operation window on startup.
    [+] Improved: Core code improvement and optimization.
    [+] Updated: GUI. (status bar, etc.)
    [-] Fixed: Runtime error when a big file is securely deleted.
    [-] Fixed: Runtime error when a file with a read-only attribute is securely deleted.
    [-] Fixed: Program freezing on big file shred.
    [-] Fixed: .lnk extension bug.

[#] 2.7.3 Build 30 (2023-02-12)

    [+] Added: Explorer shell context menu, associated with .fcr files.
    [+] Added: Feature to create a program shortcut to the desktop.
    [+] Added: Now entered password is more secure against memory attacks.
    [+] Added: Taskbar progress.
    [+] Added: Version history window to the program.
    [+] Improved: Core code improvement and optimization.
    [+] Improved: File size calculation.
    [+] Updated: GUI. (added tooltips etc.)
    [+] Updated: The source file shredder feature moved to the password window.

[#] 2.2.5 Build 18 (2023-02-08)

    [+] Added: Now full Unicode support.
    [+] Added: Show/Hide password button to the password window.
    [+] Added: Feature to abort the whole encryption/decryption operation.
    [+] Improved: Core code improvement.
    [+] Optimized: File cryptor control. (handle errors)
    [+] Updated: GUI.
    [+] Updated: Password input length limited to 32 characters.
    [-] Fixed: TaskDialog hyperlink bug.
    [-] Fixed: The minimize button bug.
    [-] Fixed: The progress bar bug when the operation starts.
    [-] Fixed: The cancel operation bug, In case the password is wrong.

[#] 2.1.1 Build 11 (2023-02-05)

    [-] Fixed: The program crashes on startup.

[#] 2.1.1 Build 10 (2023-02-05) [First Release]

    [+] Added: AES 256-bit algorithm with EAX mode.
    [+] Added: Shredder source file. (1 pass)
    [+] Added: Drag and drop support.


## Bug Reporting ##

If you found any bugs during usage, please submit the Issues.



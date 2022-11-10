# PowerShell New-ToastNotification
 A PowerShell Module to create Windows ToastNotifications


## .SYNOPSIS
Creates custom Windows Toast notifications with titles and text

## .DESCRIPTION
Creates custom Windows Toast notifications with titles and text

## .PARAMETER ApplicationTitle
Specifies the title of the application that created the Toast notification

## .PARAMETER ToastTitle
Specifies the title of the Toast notification 

## .PARAMETER ToastBody
Specifies the text of the Toast notification 

## .EXAMPLE
PS> New-ToastNotification -ApplicationTitle "PomodoroTimer" -ToastBody "Deep work ended"

## .EXAMPLE
PS> "This is body text" | New-ToastNotification

## .LINK
https://github.com/GlennToms/PowerShell-New-ToastNotification

## .LINK
https://den.dev/blog/powershell-windows-notification/

## .LINK
https://github.com/GlennToms/Powershell-Pomodoro-Timer

## .NOTES
Updated for use with Pomodoro Timer


NAME
    Start-ProcessAsAdministrator
    
SYNOPSIS
    Starts a process with the "Run as administrator" option.
    
    
SYNTAX
    Start-ProcessAsAdministrator [-FilePath] <String> [[-ArgumentList] <String[]>] [-Credential <PSCredential>] [-WorkingDirectory <String>] [-LoadUserProfile] [-NoNewWind
    ow] [-PassThru] [-RedirectStandardError <String>] [-RedirectStandardInput <String>] [-RedirectStandardOutput <String>] [-Wait] [-UseNewEnvironment] [<CommonParameters>
    ]
    
    Start-ProcessAsAdministrator [-FilePath] <String> [[-ArgumentList] <String[]>] [-WorkingDirectory <String>] [-PassThru] [-Wait] [-WindowStyle {Normal | Hidden | Minimi
    zed | Maximized}] [<CommonParameters>]
    
    
DESCRIPTION
    The Start-ProcessAsAdministrator function starts an elevated process with Administrator privileges.
    It has the same parameters as Start-Process and can be used in the same ways. 
    
    Start-ProcessAsAdministrator does not have a Verb parameter 
    because it binds the value "RunAs" to the verb parameter to set the "Run as administrator" option.
    

RELATED LINKS
    Start-Process 

REMARKS
    To see the examples, type: "get-help Start-ProcessAsAdministrator -examples".
    For more information, type: "get-help Start-ProcessAsAdministrator -detailed".
    For technical information, type: "get-help Start-ProcessAsAdministrator -full".

NAME
    Get-CurrentUser
    
SYNOPSIS
    Gets the current user.
    
    
SYNTAX
    Get-CurrentUser [<CommonParameters>]
    
    
DESCRIPTION
    The Get-CurrentUser function gets the Windows identity
    of the current user, including the user name. This function
    has no parameters.
    

RELATED LINKS

REMARKS
    To see the examples, type: "get-help Get-CurrentUser -examples".
    For more information, type: "get-help Get-CurrentUser -detailed".
    For technical information, type: "get-help Get-CurrentUser -full".

NAME
    Test-IsAdministrator
    
SYNOPSIS
    Tells whether the current user is an administrator.
    
    
SYNTAX
    Test-IsAdministrator [<CommonParameters>]
    
    
DESCRIPTION
    The Test-IsAdministrator function determines whether the current user is a member of the 
    Administrators group on the local computer.
    It returns TRUE if a user is an administrator and FALSE otherwise.
    This function has no parameters.
    

RELATED LINKS

REMARKS
    To see the examples, type: "get-help Test-IsAdministrator -examples".
    For more information, type: "get-help Test-IsAdministrator -detailed".
    For technical information, type: "get-help Test-IsAdministrator -full".

NAME
    Get-Everyone
    
SYNOPSIS
    Gets all users
    
    
SYNTAX
    Get-Everyone [<CommonParameters>]
    
    
DESCRIPTION
    Queries WMI to get all users.  To save time, queries
    are local unless the -fromDomain switch is used
    

RELATED LINKS

REMARKS
    To see the examples, type: "get-help Get-Everyone -examples".
    For more information, type: "get-help Get-Everyone -detailed".
    For technical information, type: "get-help Get-Everyone -full".





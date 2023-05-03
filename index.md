# Changing Environment Variables in PowerShell

PowerShell is a powerful scripting language that provides a comprehensive command-line environment for managing and automating Windows systems. One of the key features of PowerShell is the ability to set and manage environment variables, which are system-wide settings that control how various applications and processes behave.

In this article, we'll explore two ways to change environment variables in PowerShell: modifying the Windows registry directly with the `Set-ItemProperty` cmdlet, and setting the value programmatically using the `Environment.SetEnvironmentVariable` method. We'll also cover how to configure environment variables in both machine and user scope.

## Changing Environment Variables with Set-ItemProperty

To change environment variables using `Set-ItemProperty`, you need to modify the Windows registry directly. Here's an example of how to add a new directory to the PATH environment variable for all users on a machine:

1. Open a PowerShell console as an administrator.
2. Run the following command to add a new directory to the PATH environment variable:
This command adds `;C:\NewDirectory` to the existing value of the PATH environment variable, which is stored in the registry under the `Path` name.
3. Close and reopen the PowerShell console to see the changes take effect.

To modify environment variables in user scope, you need to modify the registry for the current user. Here's an example of how to add a new directory to the PATH environment variable for the current user:

1. Open a PowerShell console.
2. Run the following command to add a new directory to the PATH environment variable:
3. This command adds `;C:\NewDirectory` to the existing value of the PATH environment variable for the current user, which is stored in the registry under the `Path` name.
3. Close and reopen the PowerShell console to see the changes take effect.

## Changing Environment Variables with Environment.SetEnvironmentVariable

To change environment variables programmatically using `Environment.SetEnvironmentVariable`, you don't need to modify the registry directly. Here's an example of how to add a new directory to the PATH environment variable for all users on a machine:

1. Open a PowerShell console as an administrator.
2. Run the following command to add a new directory to the PATH environment variable:
This command adds `;C:\NewDirectory` to the existing value of the PATH environment variable, which is stored in the registry under the `Path` name.
3. Close and reopen the PowerShell console to see the changes take effect.

To modify environment variables in user scope, you need to modify the registry for the current user. Here's an example of how to add a new directory to the PATH environment variable for the current user:

1. Open a PowerShell console.
2. Run the following command to add a new directory to the PATH environment variable:
This command adds `;C:\NewDirectory` to the existing value of the PATH environment variable for the current user, which is stored in the registry under the `Path` name.
3. Close and reopen the PowerShell console to see the changes take effect.

## Changing Environment Variables with Environment.SetEnvironmentVariable

To change environment variables programmatically using `Environment.SetEnvironmentVariable`, you don't need to modify the registry directly. Here's an example of how to add a new directory to the PATH environment variable for all users on a machine:

1. Open a PowerShell console as an administrator.
2. Run the following command to add a new directory to the PATH environment variable:
This command adds `;C:\NewDirectory` to the existing value of the PATH environment variable for all users on the machine.
3. Close and reopen the PowerShell console to see the changes take effect.

To modify environment variables in user scope, you can use the same command but with the `User` scope instead:

1. Open a PowerShell console.
2. Run the following command to add a new directory to the PATH environment variable:
This command adds `;C:\NewDirectory` to the existing value of the PATH environment variable for the current user.
3. Close and reopen the PowerShell console to see the changes take effect.

## Conclusion

In this article, we've covered two ways to change environment variables in PowerShell: modifying the

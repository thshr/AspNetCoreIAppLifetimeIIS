# AspNetCoreIAppLifetimeIIS
Asp.NET Core 2.0 IApplicationLifetime registering cancellation tokens when hosted in IIS not working.
When IIS recycles the app pool, Stopping and Stopped callbacks are not fired!

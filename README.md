"# spring-scheduler" 

@Scheduled({options}) </br>
Need to put this at the method level which will in utrn make the framework call this method in regular intervals.
Options for scheduling
    >   Cron:              A cron-like expression, extending the usual UN*X definition to include triggers on the second as well as 
                           minute, hour, day of month, month and day of week. Refer Java Doc for <b> CronSequenceGenerator </b>
    >   Time Zone Based:   A time zone for which the cron expression will be resolved.
    >   Fixed Delay:       Execute the annotated method with a fixed period in milliseconds between the end of the last invocation and the
                           start of the next.
    >   Fixed Rate:        Execute the annotated method with a fixed period in milliseconds between invocations.
    >   Initial Delay:     Number of milliseconds to delay before the first execution of a fixedRate or fixedDelay task.

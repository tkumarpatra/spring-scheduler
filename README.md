"# spring-scheduler" 

<b>@EnableScheduling</b>: Enables Spring's scheduled task execution capability </br></br>

<b>@Scheduled({options}) </b>: Need to put this at the method level which will in utrn make the framework call this method in regular intervals.</br>
<b>options</b> for scheduling</br>
    >   Cron:              A cron-like expression, extending the usual UN*X definition to include triggers on the second as well as </br>
                           minute, hour, day of month, month and day of week. Refer Java Doc for <b> CronSequenceGenerator </b></br>
    >   Time Zone Based:   A time zone for which the cron expression will be resolved.</br>
    >   Fixed Delay:       Execute the annotated method with a fixed period in milliseconds between the end of the last invocation and the
                           start of the next.</br>
    >   Fixed Rate:        Execute the annotated method with a fixed period in milliseconds between invocations.</br>
    >   Initial Delay:     Number of milliseconds to delay before the first execution of a fixedRate or fixedDelay task.</br>

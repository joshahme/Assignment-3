# Assignment-3
ABC vs CBS political poll results
> Name <- c("Jeb", "Donald", "Ted", "Marco", "Carly", "Hillary", "Bernie")
> ABC_poll_results <- c(4, 62, 51, 21, 2, 14, 15)
> CBS_poll_results <- c(12, 75, 43, 19, 1, 21, 19)
> cat("ABC Political Poll Results:\n")
ABC Political Poll Results:
> for (i in seq_along(Name)) {
+   cat(Name[i], ":", ABC_poll_results[i], "%\n")
+ }
Jeb : 4 %
Donald : 62 %
Ted : 51 %
Marco : 21 %
Carly : 2 %
Hillary : 14 %
Bernie : 15 %
> cat("\n")

> cat("CBS Political Poll Results:\n")
CBS Political Poll Results:
> for (i in seq_along(Name)) {
+   cat(Name[i], ":", CBS_poll_results[i], "%\n")
+ }
Jeb : 12 %
Donald : 75 %
Ted : 43 %
Marco : 19 %
Carly : 1 %
Hillary : 21 %
Bernie : 19 %
> 

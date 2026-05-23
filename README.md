# HKU Elevator Estimator

This website is designed to help HKU students, staff, and visitors estimate how long they will need to wait to travel from HKU Station to the main campus. By simply entering the number of people waiting ahead of you, the tool will provide an estimated arrival time along with a prediction interval.

For advanced users, clicking the button in the top-right corner allows you to modify the estimator's underlying parameters. You can customize the number of active elevators, the time intervals for quantile calculations, the service times, and the capacity parameters.

Current Limitations

Single-Variable Focus: The model assumes that the number of people waiting is the sole factor affecting wait times, omitting other potential real-world variables.

Distribution Assumptions: It assumes that elevator service times follow an Exponentially Modified Gaussian (Exponormal) distribution and capacities follow a Weibull distribution, with each service period being independent and identically distributed (i.i.d.).

Time-Domain Specificity: The default parameters are strictly optimized for the morning peak hours. To use the estimator for the evening rush hour, users must adjust the parameters manually.

Thank you for visiting! On the left, you can find my Instagram account where I post updates on my current work. I hope you find this estimator helpful and enjoy using it!

I would love to hear your feedback on this tool or any of my other projects.














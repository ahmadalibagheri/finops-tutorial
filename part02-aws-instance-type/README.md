Hi there! 
So it’s part 2, yea we talked about Non-office time strategy in this link, and I recommend it be read first. 

<h1 style="color:yellowgreen">
Select the correct cloud instance type. 
</h1>

There are several types of EC2, and you have to choose the best option for your project because the price is so different between these types and can make you a big bill.

OnDemand Monthly prices listed for various instance types in US-East for Linux AMIs

| t3.large | m5.large  | c5.large | r5.large | i3.large  | z1d.large |
| :---     | :---      | :---     | :---     |  :---     | :---      | 
| $60.74   | $70.08    | $62.05   | $91.98   | $113.88   | $135.78   |



Let's go for a little description about our options.



<h1 style="color:yellowgreen">
T3
</h1>

These machines are generated for general purposes with an amazing combination of CPU, RAM, and network. Also, the next generation of T3 is T3a, and it's more optimized.
The most important thing about these instances is they are configured by default to increase CPU bursting without limits, yea it’s great, and it can be so helpful to prevent insufficient CPU, and you need to know about the price ;). 
You need to pay more for this feature.

It’s good for 

- If your application needs to do some huge process and your CPU usage is not measurable 


<h1 style="color:yellowgreen">
T4g
</h1>

T4g instances use a custom AWS Graviton2 processor with a 64-bit Arm core. It has an amazing performance benefit ( up to 40% at a 20% lower cost in comparison to T3), 
Providing the best price/performance for a broader spectrum of workload. 

It’s good for 
- small and medium databases 
- Virtual desktops 
- Development environments
- Code Repos
- Low-latency interactive applications



<h1 style="color:yellowgreen">
M5 and the whole family (M5a, M5n, M4)
</h1>

Do you want to run a small or midsize database and a backend application? Yea, this is a good choice for you. With a balanced CPU and memory for these purposes.
Network bandwidths are great, and you can enjoy 


<h1 style="color:yellowgreen">
M6g
</h1>

Yes, it’s a new version for all M5 family purposes. It uses  64-bit Arm-based AWS Graviton2 processors, so you have more amazing price and performance than M5 instances (up to 40%). 

<h1 style="color:yellowgreen">
Compute Optimized C4 …… C7g 
</h1>

Do you want to do some machine learning or any high-performance computing?
Do you want to do data analyses? 
Yes, this family is the best choice for you with the lowest price per CPU ratio.



<h1 style="color:yellowgreen">
Memory Optimized instances
</h1>


Do you want to deploy a streaming application? Do you have a memory burner application?
Yea, this family is the best choice for you. Real-time stream applications need more memory than other programs.



<h1 style="color:yellowgreen">
Storage Optimized Family - D2
</h1>

Do you want to have up to 48 TB HDD with high disk throughput and the lowest price? Yes, you need to choose D2 from Storage Optimized family 

- High-frequency Intel Xeon E5-2676 v3 (Haswell) processors
- HDD storage
- Consistent high performance at launch time
- High disk throughput
- Support for Enhanced Networking





There are more choices, and we can talk more about them in the future. 

Stay tuned 

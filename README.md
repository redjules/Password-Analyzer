# Password Sniffing:

I will use Wireshark for this project. 

We download Wireshark:

![Screenshot 2024-02-19 at 10 47 32](https://github.com/redjules/Password-Analyzer/assets/106017493/21a9c7be-6d88-4ca4-a424-c61c9d907583)

now we have a Npcap packet driver as a consequence of installing Wireshark:

![Screenshot 2024-02-19 at 10 50 16](https://github.com/redjules/Password-Analyzer/assets/106017493/b176a373-8d75-485d-9236-2df1596c56fa)

![Screenshot 2024-02-19 at 10 52 14](https://github.com/redjules/Password-Analyzer/assets/106017493/53b48102-5133-4843-9960-fba15de8fca9)

we filter to only see telnet traffic:


![Screenshot 2024-02-19 at 10 53 34](https://github.com/redjules/Password-Analyzer/assets/106017493/1d74878d-4211-4df4-9051-e24ac0353240)



![Screenshot 2024-02-19 at 10 54 50](https://github.com/redjules/Password-Analyzer/assets/106017493/e353cfba-2047-4a16-9711-40f90f770404)

in the TCP Stream we can see the password we typed:

![Screenshot 2024-02-19 at 10 55 24](https://github.com/redjules/Password-Analyzer/assets/106017493/6b5055a7-939f-45c9-900e-f8f9422c8344)

As an example, we put a user and password:

![Screenshot 2024-02-19 at 11 03 14](https://github.com/redjules/Password-Analyzer/assets/106017493/563c7be4-4b1b-4f80-b578-9e8713f73cf2)

we look for the traffic on that IP address:

![Screenshot 2024-02-19 at 11 01 39](https://github.com/redjules/Password-Analyzer/assets/106017493/a6b1ddba-d638-4760-bbca-0da06dd6493c)

and we get our credentials in wireshark:

![Screenshot 2024-02-19 at 11 02 32](https://github.com/redjules/Password-Analyzer/assets/106017493/3ed82205-b2b7-46e4-ab7a-9728a3a7a36b)


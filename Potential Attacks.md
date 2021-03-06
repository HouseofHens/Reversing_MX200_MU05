Potential attacks file

1. Watering hole attack on the Crucial.com website
 - Crucial is the manufacturing company for the Solid State Drive we chose to analyze. The crucial website is easily accessible by anyone seeking to learn more about Crucial
   hardware components. We found that firmware updates can be dowloaded directly from the Crucial website, thus, executing a watering hole attack on the website would allow 
   an attacker to infect users that visit the Crucial website. The watering hole attack would certainly take some hard work as it would likely require a zero-day vulnerability 
   to be found within a browser or other software extensions connected to the Crucial website. However, if one were able to execute a watering hole attack on the crucial 
   website and inject their own code into the firmware update files, they would be able to corrupt memory on the Crucial SSDs or even gain access to a shell on the victim's 
   system if the code were written correctly.
   
2. Create a fake, replica website of Crucial.com with a similar domain name and hide malicious links underneath real links
  - Another idea for an attack on the Crucial SSDs would be to create a replica of the real Crucial.com website with a similar domain name such as Cruciial.com or Cruciul.com 
    and host malicious firmware updates on that website. The fake site would include links to the firmware updates and other downloadable links that appear to be real but would
    actually be harmful. The fake website would look and feel exactly like the real Crucial.com website. This kind of attack would be more simple to implement but may not be 
    as successful as other forms of attack.
    
3. Continue to analyze harware encryption on Crucial Solid State Drives and try to bypass
  - Research suggests that encryption for hardware components like Solid State Drives may not be as secure as many believe it to be. Although our analysis has not yet proven
    any particular vulnerability, we believe further research may uncover such problems.

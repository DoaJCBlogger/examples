This repository has some example code to show what can be done with
the RSP. No warranty is given with any of this code and it is
provided as is.

play_sdr has been updated to use the new API functions and added support
for RSP1 and RSP2. Also it now supports both 8 and 16 bit output.

If you would like to make contributions to this area, please send an
email to software@sdrplay.com

------

This version has been adapted to compile with Visual Studio 2015. I've set the Linker options to include 'mir_sdr_api.lib' for x86 Debug and Release. If the project refuses to compile, check that you're set to x86.

I've also included a finished 32-bit EXE so you can use the app without compiling.

And since I'm including official SDRplay API files:

---SDRplay Copyright Notice---

Legal Information

Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following
conditions are met:

1. Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.
2. Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer
in the documentation and/or other materials provided with the distribution.
3. Neither the name of the copyright holder nor the names of its contributors may be used to endorse or promote products
derived from this software without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR
IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND
FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR
CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR
CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR
SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY
THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR
OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY
OF SUCH DAMAGE.

SDRPlay modules use a Mirics chipset and software. The information supplied hereunder is provided to you by SDRPlay
under license from Mirics. Mirics hereby grants you a perpetual, worldwide, royalty free license to use the information herein
for the purpose of designing software that utilizes SDRPlay modules, under the following conditions:
There are no express or implied copyright licenses granted hereunder to design or fabricate any integrated circuits or
integrated circuits based on the information in this document. Mirics reserves the right to make changes without further notice
to any of its products. Mirics makes no warranty, representation or guarantee regarding the suitability of its products for any
particular purpose, nor does Mirics assume any liability arising out of the application or use of any product or circuit, and
specifically disclaims any and all liability, including without limitation consequential or incidental damages. Typical parameters that may be provided in Mirics data sheets and/or specifications can and do vary in different applications and actual
performance may vary over time. All operating parameters must be validated for each customer application by the buyer’s
technical experts. SDRPlay and Mirics products are not designed, intended, or authorized for use as components in systems
intended for surgical implant into the body, or other applications intended to support or sustain life, or for any other application in which the failure of the Mirics product could create a situation where personal injury or death may occur. Should Buyer purchase or use SDRPlay or Mirics products for any such unintended or unauthorized application, Buyer shall indemnify and
hold both SDRPlay and Mirics and their officers, employees, subsidiaries, affiliates, and distributors harmless against all
claims, costs, damages, and expenses, and reasonable attorney fees arising out of, directly or indirectly, any claim of personal
injury or death associated with such unintended or unauthorized use, even if such claim alleges that either SDRPlay or Mirics
were negligent regarding the design or manufacture of the part. Mirics FlexiRF™, Mirics FlexiTV™ and Mirics™ are
trademarks of Mirics.

SDRPlay is the trading name of SDRPlay Limited a company registered in England # 09035244.
Mirics is the trading name of Mirics Limited a company registered in England # 05046393

------------------------------

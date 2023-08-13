<h1>Lab 6</h1>
<p>Andrew Hicks</p>
<p>EN.525.742</p>
<p>Johns Hopkins University</p>





<h2>Instructions:</h2>
<h3>1. Generate the project</h3>
<p><b>Windows:</b> Run <i>make_project.bat</i></p>
<p><b>Linux:</b> Run <i>make_project.sh</i></p>
<h3>2. Transfer the following files to the Zynq:</h3>
<p><i>configure_codec_2.bit.bin</i></p>
<p><i>./vivado/radio_periph_lab.runs/impl_1/design_1_wrapper.bit.bin</i></p>
<p><i>./src/linux_software/test_radio.c</i></p>
<h3>3. Run the bit.bin files on linux by typing the following commands:</h3>
<p>fpgautil -b configure_codec_2.bit.bin</p>
<p>fpgautil -b design_1_wrapper.bit.bin</p>
<h3>4. Compile and run the software</h3>
<p>gcc test_radio.c -o test_radio</p>
<p>./test_radio</p>

<h4>Notes:</h4>
<p><b>DO NOT CHANGE FILE STUCTURE!</b></p>
<p>The project will be located in the newly generated subfolder <i>vivado</i></p>

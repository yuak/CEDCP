# CEDCP
## Collection of experimental data on composite properties

The **C**ollection of **E**xperimental **D**ata on **C**omposite **P**roperties (**CEDCP**) includes datasets on electrical conductivity and dielectric constant of the composite as a function of the filler volume fraction. Mainly, the data were obtained by digitizing the experimental curves reported in the literature using the *Engauge Digitizer* program. The electrical conductivity data are expressed in *S/m*, while the permittivity values are dimensionless.

Each dataset is stored in a plain text file with the file extension *".inp"*. The input file includes a reference to the publication, the digitized figure number, information on the matrix and filler materials, the aspect ratio of the filler, units of measurement (*S/m* or *1*), and the measured data. The input file may also specify the electrical conductivity or dielectric constant of the composite components.

Initially, this collection was created to assess models of the properties of composite materials. In order to evaluate the model on multiple datasets, lists of datasets are used. The dataset list is stored in a text file with the extension *".lst"*. Several examples of lists of datasets containing data with a given composite property or filler shape are in the archive.

The [CEDCPdataCollection.odt](https://github.com/yuak/CEDCP/blob/main/CEDCPdataCollection.odt) file contains a table summarizing the datasets and references to the data sources.

If you use the CEDCP, please cite the following publication

Kovalenko, Y., & Prokhorov, Y. (2023). Methods and tools for assessing the accuracy of composite property models. Materials Today Communications. https://doi.org/10.1016/j.mtcomm.2023.107956

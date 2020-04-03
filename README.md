# Ca_imaging_public

Tiff2Mat is a "streamlined" version of the ImageAnalysis_GUI by @cdeister. It is currently undergoing testing by labmates and will likely be updated.
- Several features (global X-corr, nNMF, sorting ROI masks, importing non-Tiff file-types) are not included in this version, which is intended for use by labmates relatively unfamiliar with MatLab.
- This MatLab software runs on the MatLab App designer. This was a choice made for forward-compatibility, because MathWorks has announced intentions to stop including GUIDE in future MatLab releases.
- All three ImageAnalysis Programs (importer, roiMaker, and extractor) run on a single App interface with tabs.
- A Save Data tab has been added. This tab allows the user to save MetaData with their ROI information in a structure named 'fMetaData'. (note: this tab has been optimized for use in the Hoffman-Kim lab and may not reflect other labs' metaData)
- a quick button for data saving will save a .mat file in the same location and with the same name as the Tif it came from. 
- a clear button removes any need for the user to interact with the command window.
- a help tab answers common questions and problems. Please comment or contact me with additional questions or details that should be included.

JLSapp is a beta version of an app which houses most of the programs I use to analyse the .mat files generated above. It has not been updated for compatibility with 'axonal' or 'dendritic' ROI types.

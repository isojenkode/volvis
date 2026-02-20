# volvis
A copy of the smaller (under 25M) files in volvis.org repository maintained by Stephan Rottger at the University of Tubingen.

The data sets have been converted to Teem nrrd format using the Teem unu command.

For instance, aneurysm.nhdr was created by:
unu make -h -i aneurysm.raw.gz -c aneurism -t uchar -e gzip -s 256 256 256 -sp 1 1 1 -o aneurysm.nhdr

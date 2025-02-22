.. container::

   ======= ===============
   volcano R Documentation
   ======= ===============

   .. rubric:: Topographic Information on Auckland's Maunga Whau Volcano
      :name: volcano

   .. rubric:: Description
      :name: description

   Maunga Whau (Mt Eden) is one of about 50 volcanos in the Auckland
   volcanic field. This data set gives topographic information for
   Maunga Whau on a 10m by 10m grid.

   .. rubric:: Usage
      :name: usage

   .. code:: R

      volcano

   .. rubric:: Format
      :name: format

   A matrix with 87 rows and 61 columns, rows corresponding to grid
   lines running east to west and columns to grid lines running south to
   north.

   .. rubric:: Source
      :name: source

   Digitized from a topographic map by Ross Ihaka. These data should not
   be regarded as accurate.

   .. rubric:: See Also
      :name: see-also

   ``filled.contour`` for a nice plot.

   .. rubric:: Examples
      :name: examples

   .. code:: R

      require(grDevices); require(graphics)
      filled.contour(volcano, color.palette = terrain.colors, asp = 1)
      title(main = "volcano data: filled contour map")

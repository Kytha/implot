SET ( IMPLOT_SOURCE
      implot_demo.cpp
      implot_items.cpp
      implot.cpp
  )

SET ( IMPLOT_HEADERS
    implot.h
    implot_internal.h
  )

ADD_LIBRARY ( implot STATIC
  ${IMPLOT_SOURCE}
  ${IMPLOT_HEADERS}
  )


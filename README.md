# wpf-sfrangeslider-samples

This section describes the visual elements of the RangeSlider control and defines terms and concepts used in the RangeSlider.

- Inactive Major Tick Mark — Inactive major ticks to give the better indication between the Minimum to RangeStart and RangeEnd to Maximum.
- Inactive Minor Tick Mark — Inactive minor ticks to give the better indication between Major ticks in unselected part.
- Active Minor Tick Mark — Active minor ticks to give the better indication between Major ticks in selection part.
- Active Major Tick Mark — Active major ticks to give the better indication between the RangeStart and RangeEnd thumbs.
- Thumb — Thumb can be dragged along the track.
- Active Track — Selection range marked with RangeStart and RangeEnd thumbs.
- Inactive Track — The horizontal or vertical line is used to move the thumbs along it.
- Range Start — Thumb indicates the start of the selection range.
- Range End — Thumb indicates the end of the selection range.
- Value Label — indicates the value of the RangeSlider.

## Minimum and Maximum in WPF Range Slider (SfRangeSlider)

Gets or sets the minimum and maximum possible value of the range.

**XAML**
```
<editors:SfRangeSlider
                    Width="500"
                    Maximum="100"
                    Minimum="0" />
```

The SfRangeSlider control provides support to select the range of value using two thumbs.

## ShowRange

When ShowRange property is set to true, two thumbs are placed in the track. One thumb is used to update the start of the range selection and another thumb is used to update the end of the range selection.

It is possible to get an intermediate value before either the tick value or the step value is snapped when interacting with SfRangeSlider.

**IntermediateValue :** Gets the intermediate value. This works when ShowRange is false.

**IntermediateRangeStart:** Gets the intermediate RangeStart value.

**IntermediateRangeEnd:** Gets the intermediate RangeEnd value.

---
-api-id: M:Windows.AI.MachineLearning.Preview.LearningModelBindingPreview.Bind(System.String,System.Object)
-api-type: winrt method
---

<!-- Method syntax.
public void LearningModelBindingPreview.Bind(String name, Object value)
-->

# Windows.AI.MachineLearning.Preview.LearningModelBindingPreview.Bind

## -description
Binds a single input or output feature to a defined variable.

## -parameters
### -param name
The name of the input/output feature.

### -param value
The value of the input/output feature.

## -remarks

## -see-also

## -examples
public void PrepareBinding(LearningModelPreview model, SoftwareBitmap picture)
{
    // Bind the image
    var binding = new LearningModelBindingPreview(model);
    binding.Bind(_inputImageFeatureName, picture);
}

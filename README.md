This is original from @exponent, we only make a copy in order to fix some issues :)

TouchableNativeFeedback is not supported on iOS or Android API <=20
(below 5.0), so this component falls back to using TouchableOpacity in
those cases.

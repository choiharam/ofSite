#class ofxOscBundle


<!--
_visible: True_
_advanced: False_
_istemplated: False_
_extends: _
-->

##InlineDescription


an OSC bundle of ofxOscMessages and/or other ofxOscBundles





##Description





##Methods



###void addBundle(&element)

<!--
_syntax: addBundle(&element)_
_name: addBundle_
_returns: void_
_returns_description: _
_parameters: const ofxOscBundle &element_
_access: public_
_version_started: 007_
_version_deprecated: _
_summary: _
_constant: False_
_static: False_
_visible: True_
_advanced: False_
-->

_inlined_description: _

add another bundle to the bundle





_description: _







<!----------------------------------------------------------------------------->

###void addMessage(&message)

<!--
_syntax: addMessage(&message)_
_name: addMessage_
_returns: void_
_returns_description: _
_parameters: const ofxOscMessage &message_
_access: public_
_version_started: 007_
_version_deprecated: _
_summary: _
_constant: False_
_static: False_
_visible: True_
_advanced: False_
-->

_inlined_description: _

add a message to the bundle





_description: _







<!----------------------------------------------------------------------------->

###void clear()

<!--
_syntax: clear()_
_name: clear_
_returns: void_
_returns_description: _
_parameters: _
_access: public_
_version_started: 007_
_version_deprecated: _
_summary: _
_constant: False_
_static: False_
_visible: True_
_advanced: False_
-->

_inlined_description: _

clear bundle & message contents





_description: _







<!----------------------------------------------------------------------------->

###ofxOscBundle & copy(&other)

<!--
_syntax: copy(&other)_
_name: copy_
_returns: ofxOscBundle &_
_returns_description: _
_parameters: const ofxOscBundle &other_
_access: public_
_version_started: 007_
_version_deprecated: _
_summary: _
_constant: False_
_static: False_
_visible: True_
_advanced: False_
-->

_inlined_description: _

for operator= and copy constructor





_description: _







<!----------------------------------------------------------------------------->

###const ofxOscBundle & getBundleAt(i)

<!--
_syntax: getBundleAt(i)_
_name: getBundleAt_
_returns: const ofxOscBundle &_
_returns_description: _
_parameters: size_t i_
_access: public_
_version_started: 007_
_version_deprecated: _
_summary: _
_constant: False_
_static: False_
_visible: True_
_advanced: False_
-->

_inlined_description: _

\return the bundle at the given index





_description: _







<!----------------------------------------------------------------------------->

###ofxOscBundle & getBundleAt(i)

<!--
_syntax: getBundleAt(i)_
_name: getBundleAt_
_returns: ofxOscBundle &_
_returns_description: _
_parameters: size_t i_
_access: public_
_version_started: 0.10.0_
_version_deprecated: _
_summary: _
_constant: False_
_static: False_
_visible: True_
_advanced: False_
-->

_inlined_description: _

\return the bundle at the given index





_description: _







<!----------------------------------------------------------------------------->

###int getBundleCount()

<!--
_syntax: getBundleCount()_
_name: getBundleCount_
_returns: int_
_returns_description: _
_parameters: _
_access: public_
_version_started: 007_
_version_deprecated: _
_summary: _
_constant: False_
_static: False_
_visible: True_
_advanced: False_
-->

_inlined_description: _

\return the current bundle count





_description: _







<!----------------------------------------------------------------------------->

###const ofxOscMessage & getMessageAt(i)

<!--
_syntax: getMessageAt(i)_
_name: getMessageAt_
_returns: const ofxOscMessage &_
_returns_description: _
_parameters: size_t i_
_access: public_
_version_started: 007_
_version_deprecated: _
_summary: _
_constant: False_
_static: False_
_visible: True_
_advanced: False_
-->

_inlined_description: _

\return the message at the given index





_description: _







<!----------------------------------------------------------------------------->

###ofxOscMessage & getMessageAt(i)

<!--
_syntax: getMessageAt(i)_
_name: getMessageAt_
_returns: ofxOscMessage &_
_returns_description: _
_parameters: size_t i_
_access: public_
_version_started: 0.10.0_
_version_deprecated: _
_summary: _
_constant: False_
_static: False_
_visible: True_
_advanced: False_
-->

_inlined_description: _

\return the message at the given index





_description: _







<!----------------------------------------------------------------------------->

###int getMessageCount()

<!--
_syntax: getMessageCount()_
_name: getMessageCount_
_returns: int_
_returns_description: _
_parameters: _
_access: public_
_version_started: 007_
_version_deprecated: _
_summary: _
_constant: False_
_static: False_
_visible: True_
_advanced: False_
-->

_inlined_description: _

\return the current message count





_description: _







<!----------------------------------------------------------------------------->

### ofxOscBundle(&other)

<!--
_syntax: ofxOscBundle(&other)_
_name: ofxOscBundle_
_returns: _
_returns_description: _
_parameters: const ofxOscBundle &other_
_access: public_
_version_started: 007_
_version_deprecated: _
_summary: _
_constant: False_
_static: False_
_visible: True_
_advanced: False_
-->

_inlined_description: _







_description: _







<!----------------------------------------------------------------------------->

### ofxOscBundle()

<!--
_syntax: ofxOscBundle()_
_name: ofxOscBundle_
_returns: _
_returns_description: _
_parameters: _
_access: public_
_version_started: 007_
_version_deprecated: _
_summary: _
_constant: False_
_static: False_
_visible: True_
_advanced: False_
-->

_inlined_description: _







_description: _







<!----------------------------------------------------------------------------->

###ofxOscBundle & operator=(&other)

<!--
_syntax: operator=(&other)_
_name: operator=_
_returns: ofxOscBundle &_
_returns_description: _
_parameters: const ofxOscBundle &other_
_access: public_
_version_started: 007_
_version_deprecated: _
_summary: _
_constant: False_
_static: False_
_visible: True_
_advanced: False_
-->

_inlined_description: _







_description: _







<!----------------------------------------------------------------------------->

##Variables



###ofxOscBundle bundles

<!--
_name: bundles_
_type: ofxOscBundle_
_access: private_
_version_started: 007_
_version_deprecated: _
_summary: _
_visible: True_
_constant: True_
_advanced: False_
-->

_inlined_description: _

< bundled bundles





_description: _







<!----------------------------------------------------------------------------->

###ofxOscMessage messages

<!--
_name: messages_
_type: ofxOscMessage_
_access: private_
_version_started: 007_
_version_deprecated: _
_summary: _
_visible: True_
_constant: True_
_advanced: False_
-->

_inlined_description: _

< bundled messages





_description: _







<!----------------------------------------------------------------------------->


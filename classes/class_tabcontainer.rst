.. Generated automatically by doc/tools/makerst.py in Godot's source tree.
.. DO NOT EDIT THIS FILE, but the TabContainer.xml source instead.
.. The source is found in doc/classes or modules/<name>/doc_classes.

.. _class_TabContainer:

TabContainer
============

**Inherits:** :ref:`Container<class_Container>` **<** :ref:`Control<class_Control>` **<** :ref:`CanvasItem<class_CanvasItem>` **<** :ref:`Node<class_Node>` **<** :ref:`Object<class_Object>`

**Category:** Core

Brief Description
-----------------

Tabbed Container.

Properties
----------

+---------------------------------------------+--------------------------------------------------------------------------------+
| :ref:`int<class_int>`                       | :ref:`current_tab<class_TabContainer_current_tab>`                             |
+---------------------------------------------+--------------------------------------------------------------------------------+
| :ref:`bool<class_bool>`                     | :ref:`drag_to_rearrange_enabled<class_TabContainer_drag_to_rearrange_enabled>` |
+---------------------------------------------+--------------------------------------------------------------------------------+
| :ref:`TabAlign<enum_TabContainer_TabAlign>` | :ref:`tab_align<class_TabContainer_tab_align>`                                 |
+---------------------------------------------+--------------------------------------------------------------------------------+
| :ref:`bool<class_bool>`                     | :ref:`tabs_visible<class_TabContainer_tabs_visible>`                           |
+---------------------------------------------+--------------------------------------------------------------------------------+

Methods
-------

+--------------------------------+------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Control<class_Control>`  | :ref:`get_current_tab_control<class_TabContainer_get_current_tab_control>` **(** **)** const                                             |
+--------------------------------+------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Popup<class_Popup>`      | :ref:`get_popup<class_TabContainer_get_popup>` **(** **)** const                                                                         |
+--------------------------------+------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`int<class_int>`          | :ref:`get_previous_tab<class_TabContainer_get_previous_tab>` **(** **)** const                                                           |
+--------------------------------+------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Control<class_Control>`  | :ref:`get_tab_control<class_TabContainer_get_tab_control>` **(** :ref:`int<class_int>` idx **)** const                                   |
+--------------------------------+------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`int<class_int>`          | :ref:`get_tab_count<class_TabContainer_get_tab_count>` **(** **)** const                                                                 |
+--------------------------------+------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`bool<class_bool>`        | :ref:`get_tab_disabled<class_TabContainer_get_tab_disabled>` **(** :ref:`int<class_int>` tab_idx **)** const                             |
+--------------------------------+------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Texture<class_Texture>`  | :ref:`get_tab_icon<class_TabContainer_get_tab_icon>` **(** :ref:`int<class_int>` tab_idx **)** const                                     |
+--------------------------------+------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`String<class_String>`    | :ref:`get_tab_title<class_TabContainer_get_tab_title>` **(** :ref:`int<class_int>` tab_idx **)** const                                   |
+--------------------------------+------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`int<class_int>`          | :ref:`get_tabs_rearrange_group<class_TabContainer_get_tabs_rearrange_group>` **(** **)** const                                           |
+--------------------------------+------------------------------------------------------------------------------------------------------------------------------------------+
| void                           | :ref:`set_popup<class_TabContainer_set_popup>` **(** :ref:`Node<class_Node>` popup **)**                                                 |
+--------------------------------+------------------------------------------------------------------------------------------------------------------------------------------+
| void                           | :ref:`set_tab_disabled<class_TabContainer_set_tab_disabled>` **(** :ref:`int<class_int>` tab_idx, :ref:`bool<class_bool>` disabled **)** |
+--------------------------------+------------------------------------------------------------------------------------------------------------------------------------------+
| void                           | :ref:`set_tab_icon<class_TabContainer_set_tab_icon>` **(** :ref:`int<class_int>` tab_idx, :ref:`Texture<class_Texture>` icon **)**       |
+--------------------------------+------------------------------------------------------------------------------------------------------------------------------------------+
| void                           | :ref:`set_tab_title<class_TabContainer_set_tab_title>` **(** :ref:`int<class_int>` tab_idx, :ref:`String<class_String>` title **)**      |
+--------------------------------+------------------------------------------------------------------------------------------------------------------------------------------+
| void                           | :ref:`set_tabs_rearrange_group<class_TabContainer_set_tabs_rearrange_group>` **(** :ref:`int<class_int>` group_id **)**                  |
+--------------------------------+------------------------------------------------------------------------------------------------------------------------------------------+

Theme Properties
----------------

+---------------------------------+--------------------------------------------------------------------+
| :ref:`Texture<class_Texture>`   | :ref:`decrement<class_TabContainer_decrement>`                     |
+---------------------------------+--------------------------------------------------------------------+
| :ref:`Texture<class_Texture>`   | :ref:`decrement_highlight<class_TabContainer_decrement_highlight>` |
+---------------------------------+--------------------------------------------------------------------+
| :ref:`Font<class_Font>`         | :ref:`font<class_TabContainer_font>`                               |
+---------------------------------+--------------------------------------------------------------------+
| :ref:`Color<class_Color>`       | :ref:`font_color_bg<class_TabContainer_font_color_bg>`             |
+---------------------------------+--------------------------------------------------------------------+
| :ref:`Color<class_Color>`       | :ref:`font_color_disabled<class_TabContainer_font_color_disabled>` |
+---------------------------------+--------------------------------------------------------------------+
| :ref:`Color<class_Color>`       | :ref:`font_color_fg<class_TabContainer_font_color_fg>`             |
+---------------------------------+--------------------------------------------------------------------+
| :ref:`int<class_int>`           | :ref:`hseparation<class_TabContainer_hseparation>`                 |
+---------------------------------+--------------------------------------------------------------------+
| :ref:`Texture<class_Texture>`   | :ref:`increment<class_TabContainer_increment>`                     |
+---------------------------------+--------------------------------------------------------------------+
| :ref:`Texture<class_Texture>`   | :ref:`increment_highlight<class_TabContainer_increment_highlight>` |
+---------------------------------+--------------------------------------------------------------------+
| :ref:`int<class_int>`           | :ref:`label_valign_bg<class_TabContainer_label_valign_bg>`         |
+---------------------------------+--------------------------------------------------------------------+
| :ref:`int<class_int>`           | :ref:`label_valign_fg<class_TabContainer_label_valign_fg>`         |
+---------------------------------+--------------------------------------------------------------------+
| :ref:`Texture<class_Texture>`   | :ref:`menu<class_TabContainer_menu>`                               |
+---------------------------------+--------------------------------------------------------------------+
| :ref:`Texture<class_Texture>`   | :ref:`menu_highlight<class_TabContainer_menu_highlight>`           |
+---------------------------------+--------------------------------------------------------------------+
| :ref:`StyleBox<class_StyleBox>` | :ref:`panel<class_TabContainer_panel>`                             |
+---------------------------------+--------------------------------------------------------------------+
| :ref:`int<class_int>`           | :ref:`side_margin<class_TabContainer_side_margin>`                 |
+---------------------------------+--------------------------------------------------------------------+
| :ref:`StyleBox<class_StyleBox>` | :ref:`tab_bg<class_TabContainer_tab_bg>`                           |
+---------------------------------+--------------------------------------------------------------------+
| :ref:`StyleBox<class_StyleBox>` | :ref:`tab_fg<class_TabContainer_tab_fg>`                           |
+---------------------------------+--------------------------------------------------------------------+
| :ref:`int<class_int>`           | :ref:`top_margin<class_TabContainer_top_margin>`                   |
+---------------------------------+--------------------------------------------------------------------+

Signals
-------

  .. _class_TabContainer_pre_popup_pressed:

- **pre_popup_pressed** **(** **)**

Emitted when the ``TabContainer``'s :ref:`Popup<class_Popup>` button is clicked. See :ref:`set_popup<class_TabContainer_set_popup>` for details.

  .. _class_TabContainer_tab_changed:

- **tab_changed** **(** :ref:`int<class_int>` tab **)**

Emitted when switching to another tab.

  .. _class_TabContainer_tab_selected:

- **tab_selected** **(** :ref:`int<class_int>` tab **)**

Emitted when a tab is selected, even if it is the current tab.

Enumerations
------------

  .. _enum_TabContainer_TabAlign:

enum **TabAlign**:

- **ALIGN_LEFT** = **0**
- **ALIGN_CENTER** = **1**
- **ALIGN_RIGHT** = **2**

Description
-----------

Sets the active tab's ``visible`` property to the value ``true``. Sets all other children's to ``false``.

Ignores non-:ref:`Control<class_Control>` children.

Individual tabs are always visible unless you use :ref:`set_tab_disabled<class_TabContainer_set_tab_disabled>` and :ref:`set_tab_title<class_TabContainer_set_tab_title>` to hide it.

To hide only a tab's content, nest the content inside a child :ref:`Control<class_Control>`, so it receives the ``TabContainer``'s visibility setting instead.

Property Descriptions
---------------------

  .. _class_TabContainer_current_tab:

- :ref:`int<class_int>` **current_tab**

+----------+------------------------+
| *Setter* | set_current_tab(value) |
+----------+------------------------+
| *Getter* | get_current_tab()      |
+----------+------------------------+

The current tab index. When set, this index's :ref:`Control<class_Control>` node's ``visible`` property is set to ``true`` and all others are set to ``false``.

  .. _class_TabContainer_drag_to_rearrange_enabled:

- :ref:`bool<class_bool>` **drag_to_rearrange_enabled**

+----------+--------------------------------------+
| *Setter* | set_drag_to_rearrange_enabled(value) |
+----------+--------------------------------------+
| *Getter* | get_drag_to_rearrange_enabled()      |
+----------+--------------------------------------+

  .. _class_TabContainer_tab_align:

- :ref:`TabAlign<enum_TabContainer_TabAlign>` **tab_align**

+----------+----------------------+
| *Setter* | set_tab_align(value) |
+----------+----------------------+
| *Getter* | get_tab_align()      |
+----------+----------------------+

The alignment of all tabs in the tab container. See the ``ALIGN_*`` constants for details.

  .. _class_TabContainer_tabs_visible:

- :ref:`bool<class_bool>` **tabs_visible**

+----------+-------------------------+
| *Setter* | set_tabs_visible(value) |
+----------+-------------------------+
| *Getter* | are_tabs_visible()      |
+----------+-------------------------+

If ``true`` tabs are visible. If ``false`` tabs' content and titles are hidden. Default value: ``true``.

Method Descriptions
-------------------

  .. _class_TabContainer_get_current_tab_control:

- :ref:`Control<class_Control>` **get_current_tab_control** **(** **)** const

Returns the child :ref:`Control<class_Control>` node located at the active tab index.

  .. _class_TabContainer_get_popup:

- :ref:`Popup<class_Popup>` **get_popup** **(** **)** const

Returns the :ref:`Popup<class_Popup>` node instance if one has been set already with :ref:`set_popup<class_TabContainer_set_popup>`.

  .. _class_TabContainer_get_previous_tab:

- :ref:`int<class_int>` **get_previous_tab** **(** **)** const

Returns the previously active tab index.

  .. _class_TabContainer_get_tab_control:

- :ref:`Control<class_Control>` **get_tab_control** **(** :ref:`int<class_int>` idx **)** const

Returns the currently visible tab's :ref:`Control<class_Control>` node.

  .. _class_TabContainer_get_tab_count:

- :ref:`int<class_int>` **get_tab_count** **(** **)** const

Returns the number of tabs.

  .. _class_TabContainer_get_tab_disabled:

- :ref:`bool<class_bool>` **get_tab_disabled** **(** :ref:`int<class_int>` tab_idx **)** const

Returns ``true`` if the tab at index ``tab_idx`` is disabled.

  .. _class_TabContainer_get_tab_icon:

- :ref:`Texture<class_Texture>` **get_tab_icon** **(** :ref:`int<class_int>` tab_idx **)** const

Returns the :ref:`Texture<class_Texture>` for the tab at index ``tab_idx`` or null if the tab has no :ref:`Texture<class_Texture>`.

  .. _class_TabContainer_get_tab_title:

- :ref:`String<class_String>` **get_tab_title** **(** :ref:`int<class_int>` tab_idx **)** const

Returns the title of the tab at index ``tab_idx``. Tab titles default to the name of the indexed child node, but this can be overridden with :ref:`set_tab_title<class_TabContainer_set_tab_title>`.

  .. _class_TabContainer_get_tabs_rearrange_group:

- :ref:`int<class_int>` **get_tabs_rearrange_group** **(** **)** const

  .. _class_TabContainer_set_popup:

- void **set_popup** **(** :ref:`Node<class_Node>` popup **)**

If set on a :ref:`Popup<class_Popup>` node instance, a popup menu icon appears in the top-right corner of the ``TabContainer``. Clicking it will expand the :ref:`Popup<class_Popup>` node.

  .. _class_TabContainer_set_tab_disabled:

- void **set_tab_disabled** **(** :ref:`int<class_int>` tab_idx, :ref:`bool<class_bool>` disabled **)**

If ``disabled`` is false, hides the tab at index ``tab_idx``. Note that its title text will remain, unless also removed with :ref:`set_tab_title<class_TabContainer_set_tab_title>`.

  .. _class_TabContainer_set_tab_icon:

- void **set_tab_icon** **(** :ref:`int<class_int>` tab_idx, :ref:`Texture<class_Texture>` icon **)**

Sets an icon for the tab at index ``tab_idx``.

  .. _class_TabContainer_set_tab_title:

- void **set_tab_title** **(** :ref:`int<class_int>` tab_idx, :ref:`String<class_String>` title **)**

Sets a title for the tab at index ``tab_idx``. Tab titles default to the name of the indexed child node, but this can be overridden with :ref:`set_tab_title<class_TabContainer_set_tab_title>`.

  .. _class_TabContainer_set_tabs_rearrange_group:

- void **set_tabs_rearrange_group** **(** :ref:`int<class_int>` group_id **)**


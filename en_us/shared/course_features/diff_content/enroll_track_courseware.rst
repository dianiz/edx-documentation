:orphan:

.. _Enrollment Track Specific Courseware Overview:

#######################################################
Creating Course Content for Specific Enrollment Tracks
#######################################################

This section provides information about creating different content for
learners who are enrolled in specific enrollment tracks in your course.

.. contents::
  :local:
  :depth: 1

*********
Overview
*********

If your course has more than one enrollment track, you can create different
course experiences for learners in each enrollment track. You do this by
designating specific components in your course as visible only to learners in
one or more of the enrollment tracks. Then, learners in each of the enrollment
tracks see only the course content that you have designated for that track.

To create track-specific content in your course, follow these steps.

#. :ref:`Specify course components as visible only to particular enrollment track groups<Specify Components as Visible Only to Certain Enrollment Tracks>`
#. :ref:`View components that are available for each enrollment track group<View Components Available Based on Enrollment Track>`
#. :ref:`Preview track-specific course content<Viewing Track Specific Courseware>`


.. _About Enrollment Track Groups and Visibility:

**************************
Enrollment Track Groups
**************************

If your course offers more than one enrollment track (for example, a track
that does not offer certificates, and a certificate track where learners who
pass the course can earn a certificate), an enrollment track group is
automatically created for each enrollment track. You see these groups in
Studio, on the **Group Configurations** page.

Learners who enroll in your course in a particular enrollment track are
automatically included in the appropriate enrollment track group.

======================================
When Learners Change Enrollment Tracks
======================================

Learners select an enrollment track when they first enroll in a course, and in
many cases they will change enrollment tracks during the course run. For
example, learners might upgrade from the audit track to the verified track.

In a course where you offer differentiated content based on enrollment track,
when learners change tracks during the course run, the content that they see
changes. As soon as they change enrollment tracks, learners see only the
content that you make available to all learners and to their current
enrollment track.

As you design your course using differentiated content based on enrollment
track, be aware of maintaining the continuity of learner grades and experience
when learners change from one enrollment track to another.

.. warning:: If a learner changes enrollment tracks after having completed some
   course content in a different enrollment track, only grades from content
   that was available to all learners are kept and are reflected on the learner's
   **Progress** page.


.. _Specify Components as Visible Only to Certain Enrollment Tracks:

******************************************************************
Specify Components as Visible Only to Particular Enrollment Tracks
******************************************************************

In Studio, you can modify the visibility settings of components that you want to
make visible only to learners in particular enrollment tracks.

You specify content as visible to learners by enrollment track at the
component level in a unit. You cannot specify entire units, subsections, or
sections for visibility by enrollment track.

.. note:: You do not need to edit the visibility settings of components that
   are intended for all learners. Components that you do not explicitly
   indicate as visible to a group are visible to all learners enrolled in your
   course, regardless of the learner's enrollment track.


To specify components as visible only to learners in particular enrollment
tracks, follow these steps.

#. In Studio, select **Content**, and then select **Outline**.

#. In each unit, for each component that you want to make visible only to a
   particular enrollment track, select the **Visibility Settings** icon.

   .. image:: ../../../../shared/images/Cohorts_VisibilitySettingInUnit.png
    :alt: A component in the unit page with the Visibility Settings icon
      highlighted.
    :width: 600

#. In the **Editing visibility** dialog box, for the **Change visibility to**
   option, select **Enrollment Tracks**, and then select the checkbox for each
   enrollment track for which you want the current component to be visible.

   .. image:: ../../../../shared/images/ComponentEditVisibility.png
    :width: 400
    :alt: The visibility settings dialog box for a component, showing
      enrollment tracks selected as the option for visibility.

#. Select **Save**.

The **Visibility Settings** icon for the component is now black, and the list
of groups to which this component is visible is listed under the title.

.. image:: ../../../../shared/images/Component_VisibilitySomeGroup.png
   :alt: A component's title bar with a list of the groups to which it is
     visible, and a black visibility icon, indicating that the component has
     restricted visibility.

The publishing details for the course section in the sidebar indicate that some
content is visible only to specific groups of learners.

.. image:: ../../../../shared/images/Content_OnlyVisibleToParticularGroups.png
   :alt: Course outline sidebar showing showing a black unit visibility icon
     and the note indicating that some content in the unit is visible only to a
     particular group.
   :width: 300

For more information about previewing your course to ensure that learners in a
particular enrollment track correctly see the content intended for them, see
:ref:`Viewing Track Specific Courseware` and :ref:`Roles for Viewing Course
Content`.

.. note:: In addition to visibility settings for content groups, a learner's
   ability to see a course component also depends on whether it is marked as
   visible to staff only, whether the unit is published, and the course's
   release date. For more information about testing course content in general,
   see :ref:`Testing Your Course Content`.


.. _View Components Available Based on Enrollment Track:

*************************************************************
View Components That Are Available Based on Enrollment Track
*************************************************************

To view the components that are available to learners in each of the
enrollment tracks in your course, follow these steps.

#. In Studio, select **Settings**, and then select **Group Configurations**.

#. On the **Group Configurations** page, locate the enrollment track group for
   which you want to view the usage. Enrollment track groups are shown on this
   page only if more than one enrollment track exists in the course. Each
   enrollment track group corresponds to an enrollment track.

   The enrollment track group's box displays the number of units that are
   designated for learners in the track.

#. Click the enrollment track name to view the names of units and components
   that are designated for learners in the track.

#. Click a linked unit name to go to that unit in the course outline, where
   you can change that unit's :ref:`visibility settings<Content Hidden from
   Students>`.

For more information about previewing your course to ensure that learners in
an enrollment track correctly see the content intended for them, see
:ref:`Viewing Track Specific Courseware`.


.. _Viewing Track Specific Courseware:

**************************************
Viewing Track-Specific Course Content
**************************************

After you designate components as being visible only to the learners in
certain enrollment tracks, you can view your course content as a learner in
each enrollment track to ensure that learners in each track correctly see the
content intended for them.

.. note:: In addition to visibility settings for content groups, a learner's
   ability to see a course component also depends on whether the component is
   marked as visible to staff only, whether the unit is published, and the
   course's release date. For more information about viewing course content in
   various publishing states, see :ref:`View Published Content` and
   :ref:`Preview Unpublished Content`.

Depending on whether you want to view published content or unpublished content,
you choose either **View Live** or **Preview** from the course outline in
Studio. You can then experience the course content as a learner in a particular
group would, by selecting the **View this course as** option for a learner in
the desired enrollment track, as described in :ref:`Roles for Viewing Course
Content`.

For details see :ref:`Testing Your Course Content` and :ref:`Roles for Viewing
Course Content`.

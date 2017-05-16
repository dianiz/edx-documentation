
.. _About Divided Discussions:

###################################
About Divided Discussion Topics
###################################

This section provides information about setting up discussions that are
divided by learner groups (such as cohorts or enrollment tracks) within your
course.

.. contents::
  :local:
  :depth: 1

For overview information about discussions in a course, see :ref:`Discussions`.

For information about using cohorts in a course and managing discussions that
are divided by cohort, see :ref:`Cohorts Overview` and :ref:`Moderating
Discussions for Cohorts`.


******************************
What are Divided Discussions?
******************************

Divided discussion topics are visible to all learners, but the posts, responses,
and comments within these topics are divided so that learners participate in the
discussion only with other members of the same group (either the same cohort or
the same enrollment track).

For example, you have two enrollment tracks in your course ("Audit" and
"Verified"). If you choose to divide discussions based on enrollment track
groups, and specify that a course-wide discussion topic called "Assignments"
is divided, then although all learners see the topic, learners in the "Audit"
track interact only with posts, responses, and comments from other learners in
the "Audit" track, and learners in the "Verified" track interact only with
posts, responses, and comments from learners in the "Verified" track.

Discussion topics that are not divided are unified. All learners in the course
can see and respond to posts, responses, and comments from any other learner
in the course.

..note::  Another method of providing segregated discussion experiences for learners in your course is to use the visibility settings of discussion components, instead of dividing discussions that all learners share access to. You can add multiple discussion components and use visibility settings to make each discussion component visible only to a specific group of learners. With this method, you are not limited to choosing which single group type by which to group discussions. For more information, see XXXXXX


******************************
Setting Up Divided Discussions
******************************

In courses where either cohorts or multiple enrollment tracks are enabled, you
can choose to divide discussion topics based on group, or you can specify that the
discussion topics are unified and shared by all learners.

.. note:: You can choose only one group type (either cohorts or enrollment
   track) by which to divide discussions, even if your course both uses
   cohorts and has multiple enrollment tracks.

By default, all :ref:`course-wide discussion topics<Create CourseWide
Discussion Topics>` and :ref:`content-specific discussion topics<Create
ContentSpecific Discussion Topics>` are unified: all learners can interact
with all posts responses, and comments. You can change discussion topics of
either type to be divided or unified on the instructor dashboard in the LMS.

.. note:: In courses that started prior to April 10, 2017, in courses with
   cohorts enabled and "cohorts" selected as the type of group by which
   discussions are divided, content-specific discussion topics are by default
   divided.

.. warning:: If you change settings of discussion topics in a live course
   after learners have begun reading and contributing to discussion posts, you
   are changing their course experience. Learners might see posts that were
   previously not visible to them, or they might no longer see posts that were
   previously available to all learners.

For information about settings for discussion topics, see the following
topics.

* :ref:`Coursewide Discussion Topics and Groups`
* :ref:`Specify Whether CourseWide Discussion Topics are Divided`
* :ref:`Content Specific Discussion Topics and Cohorts`
* :ref:`Specify that All ContentSpecific Discussion Topics are Divided`
* :ref:`Specify Some ContentSpecific Discussion Topics as Divided`


.. _Coursewide Discussion Topics and Groups:

***********************************************
Course-Wide Discussion Topics and Groups
***********************************************

:ref:`Course-wide discussion topics<Create CourseWide Discussion Topics>` are
by default unified; all learners interact with each other. In some instances,
however, you might decide that it makes sense to divide some course-wide
discussion topics by group, so that only members within each group see and
respond to posts made by other learners in the same group.

For step-by-step instructions for specifying whether a course-wide discussion
topic is unified or divided, see :ref:`Specify Whether CourseWide Discussion
Topics are Divided` and XXXXXXX.


=====================================================
Example: Dividing Some Course-Wide Discussion Topics
=====================================================

In this example, you run a course that has two enrollment tracks: "Free" and
"Certificate". You create differentiated content based on enrollment track, so
that learners in each track have a complete course experience, but with
different assignments and projects.

You add three new course-wide discussion topics, so that in addition to the
system-supplied General topic, you have a total of four course-wide
discussion topics.

* General
* Course Announcements
* Assignment FAQs
* Final Project Ideas

In the General and Course Announcement topics, you and other course team
members intend to add posts and that are relevant for all learners in your
course, regardless of what enrollment track they are in. Discussions in these
topics are appropriate for a unified learner audience.

However, you want the Assignment FAQs and Final Project Ideas topics to be
divided based on enrollment track, because the assignments and final projects
that learners experience will differ based on whether they are in the audit
track or the verified track. Although all learners see course-wide discussion
topics called "Assignment FAQs" and "Final Project Ideas", discussions within
these topics are divided. Learners in the "Free" track only interact in
discussions with other "Free" track learners, and learners in the
"Certificate" track only interact in discussions with other "Certificate"
learners.

For information about specifying whether course-wide discussion topics are
divided, see :ref:`Specify Whether CourseWide Discussion Topics are Divided`.

If you divide discussions, a good practice is to also apply a naming
convention so that learners know the audience for the discussion topics before
they add any posts. For information about naming conventions, see :ref:`Apply
Naming Conventions to Discussion Topics`.


.. _Specify Whether CourseWide Discussion Topics are Divided:

**********************************************************
Specify Whether Course-Wide Discussion Topics are Divided
**********************************************************

When you :ref:`create course-wide discussion topics<Create CourseWide
Discussion Topics>`, they are by default unified, and all learners in the
course can see and respond to posts from all other learners. You can change
course-wide discussion topics to be divided, so that only members of
the same cohort can see and respond to each other's posts.

To change the cohort settings for course-wide discussion topics, follow these
steps.

#. In the LMS, select **Instructor**, then select **Cohorts**.

#. Select **Specify whether discussion topics are divided by cohort**.

#. In the **Course-Wide Discussion Topics** section, select the checkbox next
   to each course-wide discussion topic that you want to divide by cohort.
   Clear the checkbox next to each course-wide discussion topic that you want
   to make unified.

#. Select **Save**.

   The list of course-wide discussion topics is updated to show which topics
   are divided by cohort, and which are unified.

   .. image:: ../../../shared/images/CohortDiscussionsCourseWide.png
     :alt: Two course-wide discussion topics in list, one cohorted and one
       unified.
     :width: 400

For more information about managing discussions that are divided by cohort, see
:ref:`Moderating Discussions for Cohorts`.

.. _Content Specific Discussion Topics and Cohorts:

**********************************************
Content-Specific Discussion Topics and Cohorts
**********************************************

When you enable the cohort feature for a course, and :ref:`create content-specific
discussion topics<Create ContentSpecific Discussion Topics>` by
adding discussion components to units in Studio, these content-specific
discussion topics are by default unified. All learners in the course can see
and respond to posts from all other learners. You can change content-specific
discussion topics to be divided by cohort, so that only members of the same
cohort can see and respond to each other's posts.

If you want all content-specific discussion topics in your course to be always
divided by cohort, follow the steps in the topic :ref:`Specify that All
ContentSpecific Discussion Topics are Cohorted`.

If you want only some content-specific discussion topics to be divided by
cohorts, following the steps in the topic :ref:`Specify Some ContentSpecific
Discussion Topics as Cohorted`.

.. _Specify that All ContentSpecific Discussion Topics are Cohorted:

*****************************************************************
Specify that All Content-Specific Discussion Topics are Cohorted
*****************************************************************

When you first :ref:`add content-specific topics<Create ContentSpecific
Discussion Topics>` in your course, by default they are unified.

If you want all content-specific discussion topics in your course to be
divided by cohort instead of unified, follow these steps.

#. In the LMS, select **Instructor**, then select **Cohorts**.

#. Select **Specify whether discussion topics are divided by cohort**.

   .. image:: ../../../shared/images/CohortDiscussionsSpecifyLink.png
     :alt: The link in the UI to specify whether content specific discussion
        topics are divided by cohort.
     :width: 800

   In the **Content-Specific Discussion Topics** section, you see that the
   **Cohort selected content-specific discussion topics** option is selected.
   Content-specific topics that exist are listed, but none of them should
   be selected, indicating that these topics are not divided by cohort.

3. Select **Always cohort content-specific discussion topics**.

   .. image:: ../../../shared/images/CohortDiscussionsAlwaysCohort.png
     :alt: Content specific discussion topics controls with the "Always cohort
        content specific discussion topics" option selected.
     :width: 500

All content-specific discussion topics in the course are now divided by
cohort, and you cannot change the cohort settings of individual content-specific
discussion topics.

For information about changing the cohort settings for your content-specific
discussions to make all of them unified except a few, see :ref:`Specify Some
ContentSpecific Discussion Topics as Cohorted`.

.. _Specify Some ContentSpecific Discussion Topics as Cohorted:

**************************************************************************
Specify that Some Content-Specific Discussion Topics are Divided by Cohort
**************************************************************************

The default behavior for content-specific discussion topics is that they are
unified when you first :ref:`add them<Create ContentSpecific Discussion
Topics>` in your course.

To specify that only some of your content-specific discussion topics are
divided by cohort, you explicitly select only the topics that you want to
be divided by cohort.

.. warning:: If you change the cohort setting from **Always Cohort Content-Specific
   Discussion Topics** to **Cohort Selected Content-Specific
   Discussion Topics**, all content-specific discussion topics are unified,
   unless you explicitly specify that they are divided by cohort before saving
   your changes. This means that any posts that were previously divided by
   cohort and restricted to viewing, responding, and commenting by members of
   the same cohort are now visible to all learners in your course.

   If you make changes to cohort settings in a running course, be aware of the
   implications of your changes. For more details, see :ref:`Altering Cohort
   Configuration`.

To specify that only some content-specific discussion topics in your course are
divided by cohort, follow these steps.

#. In the LMS, select **Instructor**, then select **Cohorts**.

#. Select **Specify whether discussion topics are divided by cohort**.

   .. image:: ../../../shared/images/CohortDiscussionsSpecifyLink.png
    :alt: The link in the UI to specify whether content specific discussion
        topics are divided by cohort.
    :width: 800

#. In the **Content-Specific Discussion Topics** section, if it is not already
   selected, select **Cohort selected content-specific discussion topics**.

   .. warning:: If you make changes to cohort settings in a running course, be
      aware of the implications of your changes. For more details, see
      :ref:`Altering Cohort Configuration`.

   All content-specific discussion topics that you add in your course are
   unified and visible to all learners. The list of content-specific
   discussion topics becomes editable.

#. Select the checkbox next to each content-specific discussion topic that you
   want to divide by cohort.

   .. image:: ../../../shared/images/CohortDiscussionsCohortSelected.png
     :alt: Content specific discussion topics controls with the "Cohort
      selected content specific discussion topics" option selected.
     :width: 500

#. Select **Save**.

   The changes to your content-specific discussions are saved. The
   content-specific discussion topics that you selected are saved as being
   divided by cohort. All other content-specific discussion topics are unified.

For more information about managing discussions that are divided by cohort, see
:ref:`Moderating Discussions for Cohorts`.

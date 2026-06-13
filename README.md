# boyko

Invite module

#WhiteScreen
https://git.drupalcode.org/project/invite/-/merge_requests/19/diffs?commit_id=429c96949f44fbfc262cb0afaf04a055ac525d07

#Warning: Attempt to read property "value" on null in Drupal\invite\Form\InviteResendForm->buildForm() (line 108 of modules/contrib/invite/src/Form/InviteResendForm.php).
Comment string

#Error: Class "Drupal\invite_by_email\Plugin\Invite\InviteByEmail" not found in Drupal\invite\Form\InviteResendForm->submitForm() (line 127 of modules/contrib/invite/src/Form/InviteResendForm.php).
Comment string

#Error: Class "Drupal\invite_by_email\Plugin\Invite\InviteByEmail" not found in Drupal\invite\Form\InviteResendForm->submitForm() (line 128 of modules/contrib/invite/src/Form/InviteResendForm.php).
Comment string

web/modules/contrib/invite/src/Controller/InviteAccept.php
55 - delete "EventDispatcher"

web/modules/contrib/invite/invite.module
28 - $data = unserialize(\Drupal::config('invite.invite_type.' . $invite->get('type')->getString())->get('data') ?? '', ['allowed_classes' => FALSE]);

web/modules/contrib/invite/src/Controller/InviteList.php
Comment strings 91 and 123

3D Flipbook module

#TypeError: Drupal\flipbook\Form\ChoosePdfStyleForm::__construct():
https://www.drupal.org/project/flipbook/issues/3508651
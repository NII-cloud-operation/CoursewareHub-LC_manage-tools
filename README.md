# CoursewareHub-LC_manage-tools

The management notebooks for CoursewareHub.

# How to deploy the notebooks to your CoursewareHub

Please log in to CoursewareHub as a teacher(an administrator) for the following operations.

Clone this repository to local.

    $ git clone https://github.com/NII-cloud-operation/CoursewareHub-LC_manage-tools.git

Run the ansible playbook named `deploy.yml`.

    $ cd CoursewareHub-LC_manage-tools
    $ ansible-playbook -i ~/ansible/inventory deploy.yml

You can execute these operations in Jupyter Notebook or Jupyter terminal.
